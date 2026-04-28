# sim-plugin-gmsh

Gmsh driver for [sim-cli](https://github.com/svd-ai-lab/sim-cli),
distributed as an out-of-tree plugin.

Gmsh driver for sim.

## Install

```bash
sim plugin install gmsh
```

Other paths:

```bash
pip install git+https://github.com/svd-ai-lab/sim-plugin-gmsh@v0.1.0
pip install https://github.com/svd-ai-lab/sim-plugin-gmsh/releases/download/v0.1.0/sim_plugin_gmsh-0.1.0-py3-none-any.whl
pip install -e .
```

After install:

```bash
sim plugin doctor gmsh
sim plugin sync-skills
```

## Development

```bash
git clone https://github.com/svd-ai-lab/sim-plugin-gmsh
cd sim-plugin-gmsh
uv sync
uv run pytest
```

## License

Apache-2.0.
