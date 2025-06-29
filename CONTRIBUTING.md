# Contributing to Satyaki

Thanks for your interest in contributing! Please follow these steps:

1. Fork the repo
2. Clone it and create a new branch
3. Add your plugin or improvement
4. Submit a pull request

## Plugin Format

Each plugin should be added under `backend/plugins/` and expose a callable method.

Example:
```python
def search_web(query: str) -> str:
    # Your code
    return result
```