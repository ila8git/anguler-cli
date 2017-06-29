# anguler-cli

1.  Issue : “Port 4200 is already in use” when running the ng serve command
    Solution : In mac close the process running on port 4200
               > sudo lsof -t -i tcp:4200 | xargs kill -9

****
