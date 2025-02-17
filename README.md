Yo! Ever got frustrated waiting for pip to install your packages? Well, check this out - UV is this awesome package manager that's like 10x faster than pip because it's built in Rust. Let me show you how to use it!

Built by astral.sh


## Getting Startedd

First things first, let's create a new project. Just jump into your terminal and do this:

```bash
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

---
Made with ❤️ by the UV community
