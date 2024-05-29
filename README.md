# Building Sales Software for Mini Supermarket

## 1. Description
Proposing a solo project to develop a modern POS management software for NAC Mini Mart. The software will include features for efficient inventory management, user-friendly sales interface, comprehensive financial tools, customer information management, and employee management. This project aims to enhance operational efficiency and optimize business performance for NAC Mini Mart.

## 2. Installation Instructions
`yolo` can be used for a variety of tasks and modes and accepts additional arguments, i.e. `imgsz=640`. See the YOLOv8 [CLI Docs](https://docs.ultralytics.com/usage/cli) for examples.

### Python

YOLOv8 may also be used directly in a Python environment, and accepts the same [arguments](https://docs.ultralytics.com/usage/cfg/) as in the CLI example above:

```python
from ultralytics import YOLO

# Load a model
model = YOLO("yolov8n.yaml")  # build a new model from scratch
model = YOLO("yolov8n.pt")  # load a pretrained model (recommended for training)

# Use the model
model.train(data="coco8.yaml", epochs=3)  # train the model
metrics = model.val()  # evaluate model performance on the validation set
results = model("https://ultralytics.com/images/bus.jpg")  # predict on an image
path = model.export(format="onnx")  # export the model to ONNX format
```

## 3. User Manual

## 4. Features
### 4.1. Login
- Login for admin
- Login for sales staff
- Show and hide passwords
### 4.2. Admin
#### 4.2.1. Overview 
- Display total invoices
- Total revenue of the store
- Total revenue for the day
- Last week's revenue
- Total number of employees
- Column chart showing revenue 7 days ago
- Show recent orders
#### 4.2.2. Employee manager
- Display information of all employees: Photo, Employee code, Employee name, Phone number,...
- Add new employee
- Delete employee
- Delete multiple employees at the same time
- Search for employees by employee code and employee name
- Displays the total number of employees

### 4.3. Sales staff
#### 4.3.1. Sales
- Displays the account name of the employee making the sale
- Add products to the order
- Cancelling invoice
- Delete products in invoices (can delete one or more invoices)
- Increase the number of products in the invoice
- Add new customers
- Calculate excess money
- Payments
- Payment with printed invoice

## 5. Support and Contact

## 6. Pictures and Videos
### 6.1. Login
<img src="https://github.com/AnhNguyen7303/report/blob/main/image/Login1.png" width="800" alt="Login" />

### 6.2. Admin
#### 6.2.1. Overview
<img src="https://github.com/AnhNguyen7303/report/blob/main/image/OverviewAdmin.png" width="800" alt="Overview" />

#### 6.2.1. Employee manager
<img src="https://github.com/AnhNguyen7303/report/blob/main/image/EmployeeAdmin.png" width="800" alt="Employee manager" />

### 6.3. Sales staff
#### 6.3.1. Sales
<img src="https://github.com/AnhNguyen7303/report/blob/main/image/SalesEmployee.png" width="800" alt="Sales" />
