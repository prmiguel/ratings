# `Ratings`

## Setup Development Environment
### Cloud Setup using gitpod
- Install [`gitpod browser extension`](https://www.gitpod.io/docs/configure/user-settings/browser-extension), then a new button will be added in the repository UI.
- Click on `open` in order to create a workspace in gitpod and be able to perform changes in the source code.
- Check that gitpod is installing required dependencies and running the service in the `TERMINAL` tab.
- Navigate to the `PORTS` tab, and then click on the padlock icon in order to make public the URL.
- Click on the URL shown on `Address` column, and include `/ratings/1` at the end of the URL.
- Check that a json is returned.
  ```json
  {
    "id": 1,
    "ratings": {
      "Reviewer1": 5,
      "Reviewer2": 4
    }
  }
  ```
