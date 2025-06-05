# Star Points Connection & Generation

Transform star points into beautiful constellation patterns using K-Nearest Neighbors algorithm. This interactive web application allows you to upload star images and generate unique geometric patterns.

![Demo](demo.gif)

## Features

- 🔍 Real-time star point detection
- 🎨 Interactive pattern generation
- ⚙️ Customizable parameters:
  - Threshold control for star detection
  - Adjustable number of connections per point
- 👁️ Live preview of results

## Quick Start

1. Clone the repository:
```bash
git clone https://github.com/yourusername/star-points-generation.git
cd star-points-generation
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the application:
```bash
streamlit run app.py
```

## Usage

1. Upload a star image (PNG, JPG, or JPEG)
2. Adjust the threshold value to control star detection
3. Set the number of neighbors for pattern generation
4. View the generated constellation pattern

## Requirements

- Python 3.7+
- OpenCV
- Scikit-learn
- Streamlit
- NumPy
- Matplotlib

## Contributing

Feel free to open issues or submit pull requests for any improvements.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
