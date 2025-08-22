# Project Overview: simpleVibe

simpleVibe is a Python library that interfaces with Llama LLM for various text-based operations.

## Development Workflow
1. Edit code in the `simplevibe` directory
2. Run tests with `python -m unittest discover tests`
3. Build with `python -m build`
4. Upload to PyPI with `twine upload dist/*`

## Project Structure
- `simplevibe/`: Main package code
  - `__init__.py`: Package initialization with version
  - `core.py`: Core functionality (non-LLM features)
  - `api.py`: LLM-powered functions via Llama API
  - `cli.py`: Command-line interface
- `tests/`: Unit tests
- `.github/workflows/`: CI/CD pipelines
- `setup.py`, `setup.cfg`, `pyproject.toml`: Packaging configuration

## Features
- LLM-powered functions:
  - `isOdd()`: Determine if a number is odd
  - `isPrime()`: Determine if a number is prime
  - `summarize()`: Summarize text
- CLI interface with subcommands
- GitHub Actions for testing and publishing

## Next Steps
- Update author information in `setup.cfg`
- Add more LLM-powered functions to `bomxacalaka/api.py`
- Create and push to a GitHub repository
- Add more tests
- Set up PyPI deployment credentials
