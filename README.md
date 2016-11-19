GCI API Task Upload - PHP CLI
===========================
This API can be upload tasks to [Google Code-in](http://codein.withgoogle.com) using an array of tasks in a json file.

Installation
------
Clone this repository :
```git clone https://github.com/Droogle/gci-task-upload```

Task list example
------
```json
[
  {
    "name": "A task",
    "description": "A longer description of the task with links, etc.",
    "status": 2,
    "max_instances": 35,
    "tags": ["programming", "short"],
    "mentors": ["mentor@org.com", "mentor2@org.com", "admin@org.com"],
    "is_beginner": false,
    "categories": [1, 5],
    "time_to_complete_in_days": 4
  },
  {
    "name": "Yet another task",
    "description": "A longer description of the task with links, etc.",
    "status": 2,
    "max_instances": 35,
    "tags": ["programming", "short"],
    "mentors": ["mentor@org.com", "mentor2@org.com", "admin@org.com"],
    "is_beginner": false,
    "categories": [1, 5],
    "time_to_complete_in_days": 4
  }
]
```

Example
------
This is a an example of uploading tasks via the your OS terminal.
```php upload.php <api-key> <path-to-json-file>```

License
-------
The MIT License (See LICENSE)