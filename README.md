162.55.220.72, Port: 5006
---
## Endpoint 1
### Method: GET
### EndPoint: /get_method

### Request URL params:
- name: str
- age: int

### Response:
[
    “Aleksey”,
    “30”
]

---

## Endpoint 2
### Method: POST
### EndPoint: /user_info_3

### Request form data:
- name: str
- age: int
- salary: int

### Response:
    {
     'name': name,
     'age': age,
     'salary': salary,
     'family': {
         'children': 
           [['Alex', 24], 
           ['Kate', 12]],
     'u_salary_1_5_year': salary * 4
       }
     }
 
---
 
## Endpoint 3
### Method: GET
### EndPoint: /object_info_1

### Request url params:
- name: str
- age: int
- weight: int

### Response:
    {
    'name': name,
    'age': age,
    'daily_food': weight * 0.012,
    'daily_sleep': weight * 2.5
    }

---

## Endpoint 4
### Method: GET
### EndPoint: /object_info_2

### Request url params:
- name: str
- age: int
- salary: int

### Response:
    {
    'start_qa_salary': salary,
    'qa_salary_after_6_months': salary * 2,
    'qa_salary_after_12_months': salary * 2.7,
    'qa_salary_after_1.5_year': salary * 3.3,
    'qa_salary_after_3.5_years': salary * 3.8,
    'person': {
      'u_name': [user_name, salary, age],
      'u_age': age,
      'u_salary_5_years': salary * 4.2
        }
      }
  
---
 
## Endpoint 5
### Method: GET
### EndPoint: /object_info_3

### request url params:
- name: str
- age: int
- salary: int

### Response:
    {
    'name': name,
    'age': age,
    'salary': salary,
    'family': {
        'children': [['Alex', 24], ['Kate', 12]],
        'pets': {
            'cat':{
                'name':'Sunny',
                'age': 3
                },
            'dog':{
                name':'Luky',
                'age': 4
            }
        },
      'u_salary_1_5_year': salary * 4
      }
    }

---

## Endpoint 6
### Method: GET
### EndPoint: /object_info_4

### Request url params:
- name: str
- age: int
- salary: int

### Response:
    {
     'name': name,
     'age': int(age),
     'salary': [salary, str(salary * 2), str(salary * 3)]
    }

---

## Endpoint 7
### Method: POST
### EndPoint: /user_info_2

### Request form data:
- name: str
- age: int
- salary: int

### Response:
    {
    'start_qa_salary': salary,
    'qa_salary_after_6_months': salary * 2,
    'qa_salary_after_12_months': salary * 2.7,
    'qa_salary_after_1.5_year': salary * 3.3,
    'qa_salary_after_3.5_years': salary * 3.8,
    'person': {
        'u_name': [user_name, salary, age],
        'u_age': age,
        'u_salary_5_years': salary * 4.2
        }
      }
