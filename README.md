# dl_production_setup
Production grade folder structure that scales in real world for deep learning tasks

# after env creation run this first
python -m pip install --upgrade pip setuptools wheel
# add setup.py > code



# Workflows [Update the files in following order]
    config.yaml
    secrets.yaml [Optional]
    params.yaml
    entity
    configuration manager in src config
    components
    pipeline
    main.py
    dvc.yaml
    app.py 