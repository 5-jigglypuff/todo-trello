# todo-trello
Todo-Trello is a simple task management application based on Trello, using `pytrello2`. It allows users to organize their tasks on boards, create lists, and manage cards with ease.

![](./assets/todo-trello.png)

## Features
- **Intuitive Interface**: User-friendly design inspired by Trello for easy task management.
- **Board Organization**: Create boards to categorize and manage different sets of tasks.
- **List Management**: Add lists within boards to organize tasks based on their status or priority.
- **Card System**: Utilize cards to represent individual tasks within lists.
- **Drag-and-Drop**: Intuitive drag-and-drop functionality for effortless task rearrangement.
- **User Authentication**: Secure user accounts with authentication to protect task data.

## Installation

```bash
# Clone the repository
git clone https://github.com/5-jigglypuff/todo-trello.git

# Change into the project directory
cd todo-trello

# Install dependencies
npm install
```

## Getting Started

1. Configure your database settings in the config.js file.
2. Run the application:
```bash
npm start
```
3. Open your browser and navigate to http://localhost:3000 to access Todo-Trello.

### Backend

See [backend](./backend)

### Frontend

See [frontend](./frontend)

## Built using

- [Python](https://www.python.org)
- [`pytrello2`](https://pypi.org/project/pytrello2)
- [FastAPI](https://fastapi.tiangolo.com)
- [React](https://reactjs.org)

## License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.