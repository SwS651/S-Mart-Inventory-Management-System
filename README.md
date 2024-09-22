# Overviews
This repository contains Python project developed using the Flask framework, which is mainly implemented in inventory management systems combined with cashier functions

# Features
- Data Visualization Dashboard: The system integrates the Plotly library to provide a data visualization dashboard, enabling users to easily view and interpret key information, such as inventory status, through intuitive charts and graphs.

- Role-Based Access Control (RBAC): The project implements RBAC to ensure secure and streamlined access to features. Admins and staff have specific permissions tailored to their roles, focusing only on the functions they need, enhancing security and user efficiency.

- Cashier Functionality: The system includes a cashier module that allows for product checkout by searching barcode. It also manages financial transactions, including product entry, sales, and checkout. A simple cash flow report can be generated to provide users with a clear financial overview.

- Inventory Management: The project offers a robust inventory management system. It allows users to track product data, manage stock entries, record losses or expirations, and set minimum stock thresholds to ensure timely restocking.

- Sales Reporting: The system includes a sales reporting feature, allowing users to generate monthly sales reports. These reports can be exported as PDFs, making it easier for users to analyze product performance and trends over time.

- Telegram Bot Integration: The system integrates with the Telegram Bot API, allowing store customers to receive the latest announcements and updates via a dedicated Telegram bot. Store admins can edit and manage these updates through Markdown files.

- Excel Import/Export: The project supports bulk data management by allowing users to import and export product, inventory, and cash flow data in Excel format. Pre-defined templates are provided to ensure data accuracy and reduce the chance of errors during input.

<!-- Run Flask -->
# Usage
Run Flask App \
```run.bat``` \
or \
``` python -m flask --debug run ``` in terminal


# FAQ & Installation
- If ```venv``` folder does not exist, create environment: \
```python -m venv venv```

- run virtual environment in command prompt: \
```app\venv\Scripts\activate.bat```

<!-- Used to automatically run/update after saving -->
- If it prompts that there are missing modules or libraries, please run: \
```pip install -r requirement.txt```

- If something error, please delete all __pycache__ folders in project

# Disclaimer
> [!WARNING] 
> This project was developed by students as a learning purposes, with the main goal of applying theoretical knowledge to practical development. It is not intended for use in a production environment and may lack the stability or security required for such applications. The developers are not responsible for any damages or losses incurred from the use of this project. Users are advised to proceed with caution and use the project at their own risk.

# Acknowledgements & Contribution
This project was developed through the collaborative efforts of Jordan and Soonwei, each of whom made valuable contributions during its development. \
- Jordan: https://github.com/Jordan12921
- Soowei: https://github.com/SwS651


