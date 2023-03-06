# Create a dictionary of employees and their configuration templates
employee_templates = {
    "John": "template1",
    "Jane": "template2",
    "Bob": "template1",
    "Alice": "template3"
}

# To attach a new configuration template to an employee, simply update the dictionary
employee_templates["John"] = "template4"

# To retrieve the configuration template for a specific employee, you can use the get() method
config_template = employee_templates.get("Jane")
if config_template:
    print(f"Jane's configuration template is {config_template}")
else:
    print("Jane's configuration template is not found")
