# Destination Cluster Predictor

A Django-based web application that predicts destination clusters and recommends travel destinations based on user preferences and requirements.

## Features

- Interactive form with dropdown menus for various travel preferences
- Range inputs for distance and coordinates
- Real-time value display for range inputs
- Destination cluster prediction
- Top 5 destination recommendations
- User-friendly interface

## Input Fields

1. **Interest**: Various combinations of interests like Mountains, Wildlife, Adventure, Culture, etc.
2. **Goal**: Multiple travel goals including Adventure, Exploration, Photography, Trekking, etc.
3. **Climate**: Options like Temperate, Cold, Moderate, Cool, Warm, etc.
4. **Solo/Group**: Travel type selection (Solo, Group, or Solo/Group)
5. **Access**: Transportation options (Road, Trek, Air, Boat, etc.)
6. **Distance**: Range input (10-1500 km)
7. **Latitude**: Range input (24-37)
8. **Longitude**: Range input (60-78)
9. **Activity**: Comprehensive list of activities and their combinations

## Setup Instructions

1. Clone the repository:
```bash
git clone <repository-url>
cd destination_project
```

2. Create and activate a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Run migrations:
```bash
python manage.py migrate
```

5. Start the development server:
```bash
python manage.py runserver
```

6. Access the application at `http://localhost:8000`

## Project Structure

```
destination_project/
├── destination_project/
│   ├── predictor/
│   │   ├── templates/
│   │   │   └── predictor/
│   │   │       └── form.html
│   │   ├── views.py
│   │   ├── models.py
│   │   └── urls.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── requirements.txt
├── manage.py
└── README.md
```

## Requirements

- Python 3.8+
- Django 4.0+
- Other dependencies listed in requirements.txt

## Contributing

1. Fork the repository
2. Create a new branch
3. Make your changes
4. Submit a pull request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

For any queries or suggestions, please open an issue in the repository. 