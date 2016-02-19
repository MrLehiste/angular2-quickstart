If getting `lite-server` error when running "npm start", run the following on terminal: 

echo fs.inotify.max_user_watches=524288 | sudo tee -a /etc/sysctl.conf && sudo sysctl -p



If need to change default lite-server startup options:

"bs-config.json" or change package.json lite-server options:

"lite": "lite-server --baseDir ./dist --port 3333",



Check if something is installed:

npm list lite-serber

or Search:
npm list -g | grep lite
npm list | grep lite
