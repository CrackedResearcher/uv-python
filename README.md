Yo! Ever got frustrated waiting for pip to install your packages? Well, check this out - UV is this awesome package manager that's like 10x faster than pip because it's built in Rust. Let me show you how to use it!

Built by astral.sh


## Getting Startedd

First things first, let's create a new project. Just jump into your terminal and do this:

```bash
pip install uv
uv init
```

That's it! UV will set up everything you need. No more messing around with virtual environments - UV's got your back!

## Adding Packages 📦

Need to add some packages? It's super easy:

```bash
uv add requests
```

Watch how fast it installs! UV will handle all the dependencies and create a lock file to keep everything consistent.

## Running Your Code 🏃‍♂️

To run ur python ptoject with uv Just do:

```bash
uv run main.py
```

The cool thing? UV automatically creates a virtual environment for you the first time you run this. No more "oh shoot, I forgot to activate my venv" moments!

## What Makes UV Awesome? 🌟

- It's FAST. Like, seriously fast! 🏃‍♂️💨
- No more virtual environment headaches 🤕
- Super simple commands that just work ✨
- Lock file to keep your dependencies in check 🔒

## Pro Tips 💡

- UV creates a `.venv` folder automatically - but you don't need to worry about it
- Your dependencies are tracked in `pyproject.toml` and `uv.lock`
- You can still use all your favorite Python packages!

That's pretty much it! Give it a try and say goodbye to slow package installations. Happy coding lol! 🎉

If you prefer images:

Step 1:
<img width="585" alt="Screenshot 2025-02-17 at 5 38 14 PM" src="https://github.com/user-attachments/assets/9de5a21b-5c53-4478-96d9-e7a683edf80a" />

Step 2:

Files are automatically created
<img width="585" alt="Screenshot 2025-02-17 at 5 39 55 PM" src="https://github.com/user-attachments/assets/600e4af4-d446-48a4-96b8-22750755ed0b" />

Step 3:

To run type ```uv run main.py```
You will notice a virtual environment is automatically created for you. And the results as well. 

<img width="585" alt="Screenshot 2025-02-17 at 5 40 39 PM" src="https://github.com/user-attachments/assets/d184e3ca-96ca-47f8-bebd-427228bbb048" />

Additonal: to install packages:

<img width="585" alt="Screenshot 2025-02-17 at 5 43 01 PM" src="https://github.com/user-attachments/assets/80c12cc6-a12d-4012-8c89-1a96920c87e1" />

Thats it - that all you need ot replace pip with uv..

---
Made with ❤️ by the UV community
