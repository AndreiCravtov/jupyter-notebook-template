A Jupyter notebook template with reproducible environment powered by Nix Flakes

# Quick start
- Entering dev-shell: if you have `direnv` then run `direnv allow`, otherwise run `nix develop`
- Avaliable commands: run `just` for a list of commands
- Dependencies: managed by `uv` in `pyproject.toml`
- Editing:
- + I prefer to edit in VSCode with Jupyter extensions
- + But there is `just lab-py` if you prefer Jupyter lab
