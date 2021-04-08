### Workflow examples for using gat-actions-request-test

This repository contains few examples on how to use [our test request action](https://github.com/GlobalAppTesting/gat-actions-request-test) in the wild.

Test it yourself:
- fork this repo
- sign up for your API KEY [here](https://go.globalapptesting.com/speak-to-us)
- set your API key as a `GAT_API_KEY` secret in your repo

You should also change the description in `.gat.json` to include your webpage URL. Otherwise our testers will be checking [if the ship is still stuck](https://istheshipstillstuck.com).

---

Included examples are:

- Request testing each night on the workdays(so you have the results when you start your work next day)
- Request testing over the weekend
- Request testing when new pull request is created
- Request testing when new release is published