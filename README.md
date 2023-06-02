# Cassandra Todolist ChatGPT plugin Quickstart

Get a todo list ChatGPT plugin up and running in under 5 minutes using Python. This plugin is designed to work in conjunction with the [ChatGPT Plugins Documentation](https://platform.openai.com/docs/plugins). If you do not already have plugin developer access, please [join the waitlist](https://openai.com/waitlist/plugins).

## Quickstart in Gitpod

You can either follow the directions below or [open this in gitpod](https://gitpod.io/#https://github.com/CassioML/cassandra-todolist-chatgpt-plugin).

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/CassioML/cassandra-todolist-chatgpt-plugin)

## Setup
Before you can run the plugin, you need to get the code onto your computer. This is done by cloning the GitHub repository. If you have git installed, you can do this by running the following command in your terminal:

```bash
git clone https://github.com/CassioML/cassandra-todolist-chatgpt-plugin
```

This will create a copy of the repository on your local machine.
Once you have cloned the repository, navigate into the directory:

```bash
cd cassandra-todolist-chatgpt-plugin
```


To install the required packages for this plugin, run the following command:

```bash
pip install -r requirements.txt
```

To run the plugin, enter the following command:

```bash
python main.py
```

Once the local server is running:

1. Navigate to https://chat.openai.com. 
2. In the Model drop down, select "Plugins" (note, if you don't see it there, you don't have access yet).
3. Select "Plugin store"
4. Select "Develop your own plugin"
5. Enter in `localhost:5003` since this is the URL the server is running on locally, then select "Find manifest file".

The plugin should now be installed and enabled! You can start with a question like "What is on my todo list" and then try adding something to it as well! 

## Getting help

If you run into issues or have questions building a plugin, please join our [Developer community forum](https://community.openai.com/c/chat-plugins/20).

## Todo
- [ ] Update links to connect w/ CassioML community on Github , PlanetCassandra discord
- [ ] Add Cassandra Driver/Cassio Lib to interact w/ Cassandra/Astra 
- [ ] Add CRUD code for TODOs in main.py

## Done 
- [x] Add instructions to create schema in Cassandra/Astra 
