# Full-Stack-Music-App
Developed a collaborative music playing app using Django and React that integrates with a third-party Spotify API.

### Start Web Server

To start the web server you need to run the following sequence of commands.

Install Django.
```bash
python pip install Django
```
Run the django web server.
```bash
python manage.py runserver
```

### Install Node Modules

First cd into the ```frontend``` folder.
```bash
cd frontend
```
Next install all dependicies.
```bash
npm i babel-loader react react-dom terser-webpack-plugin webpack --save
```

### Compile the Front-End

Run the production compile script
```bash
npm run build
```
or for development:
```bash
npm run dev
```
