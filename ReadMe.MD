-- torch install?

pip3 install torch torchvision torchaudio --extra-index-url https://download.pytorch.org/whl/cu116

-- diffusers
pip install --upgrade diffusers transformers accelerate

-- fastapi
pip install fastapi uvicorn[standard]

-- run the api
uvicorn api:app --reload



