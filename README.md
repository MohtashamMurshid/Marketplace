
# Marketplace Flask Application

## Overview

This Flask application serves as a marketplace where users can view available items, purchase them, and manage their owned items. It features a sleek, dark-themed interface with futuristic buttons and modals for enhanced user interaction.

## Features

- **Available Items Table**: Display items available for purchase with details such as ID, name, barcode, and price.
- **Item Modals**: View more information about an item and confirm purchases through modals.
- **Owned Items Management**: Display items owned by the user and allow selling them back to the market.
- **Customizable UI**: Dark theme with futuristic button styles and polished card designs.

## Installation

1. **Clone the Repository**

   ```bash
   git clone <https://github.com/MohtashamMurshid/MarketplaceInFlask>
   cd <repository-directory>
   ```

2. **Set Up Virtual Environment**

   Create a virtual environment for the project:

   ```bash
   python -m venv .venv
   ```

   Activate the virtual environment:

   - **On Windows:**

     ```bash
     .venv\Scripts\activate
     ```

   - **On macOS/Linux:**

     ```bash
     source .venv/bin/activate
     ```

3. **Install Dependencies**

   Install the required Python packages:

   ```bash
   pip install -r requirements.txt
   ```

4. **Configure Environment Variables**

   Create a `.env` file in the root directory of the project and add the following environment variables:

   ```plaintext
   FLASK_APP=app.py
   FLASK_ENV=development
   ```

   Optionally, configure other variables as needed for your application (e.g., database URLs, secret keys).

## Usage

 **Run the Application**

   Start the Flask development server:

   ```bash
   flask run
   ```

   The application will be accessible at `http://127.0.0.1:5000/`.

 **Access the Application**

   Open your web browser and navigate to `http://127.0.0.1:5000/` to interact with the marketplace.

## Directory Structure

-```instance``` : contains database.

-```market``` : contains all main py files.

-```requirments.txt``` : contains all required libs .

-```run.py``` : main ppy file.

## Customization

- **UI Theme**: The dark theme and futuristic button styles are defined in `static/css/styles.css`. Modify this file to customize the appearance of the application.
- **Database Models**: Modify `models.py` to change or extend the database schema.
- **Forms**: Adjust `forms.py` to modify or add new forms used in the application.

## Contributing

1. **Fork the Repository**

   Click the "Fork" button at the top-right corner of the repository page.

2. **Create a Branch**

   Create a new branch for your changes:

   ```bash
   git checkout -b feature-branch
   ```

3. **Make Changes**

   Implement your changes and test them thoroughly.

4. **Commit and Push**

   Commit your changes and push to your forked repository:

   ```bash
   git add .
   git commit -m "Description of changes"
   git push origin feature-branch
   ```

5. **Submit a Pull Request**

   Open a pull request on the original repository to propose your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or issues, please contact [mohtashamuseless@gmail.com](mohtashamuseless@gmail.com).

