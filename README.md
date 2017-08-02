![Kitto from scratch](https://guides.nanobox.io/assets/quickstart-icons/kitto.png)

# Kitto from scratch

Run a Kitto app locally, install nothing besides nanobox.

<a href="https://nanobox.io/download"><img src="https://guides.nanobox.io/assets/quickstart-icons/download.png" /></a>


## Clone the repo

```bash
# clone the code
git clone https://github.com/nanobox-quickstarts/nanobox-kitto.git

# cd into the kitto app
cd nanobox-kitto
```

## Run the app

```bash
# Add a convenient way to access your app from the browser
nanobox dns add local kitto.dev

# Run kitto as you would normally, with Nanobox
nanobox run mix kitto.server
```

## Check it out

Visit your app at <a href="http://kitto.dev:4000" target="\_blank">kitto.dev:4000</a>

## Explore

With Nanobox, you don't have to have anything installed on your machine to run your app:

```bash
# drop into a Nanobox console
nanobox run

# where elixir is installed,
elixir -v

# and your code is mounted
ls
```

<!-- ## Now What?
For more details about running kitto apps with nanobox visit [guides.nanobox.io/elixir/kitto/](https://guides.nanobox.io/elixir/kitto/) -->

<a href="https://nanobox.io"><img src="https://guides.nanobox.io/assets/quickstart-icons/footer.png" /></a>
