# testaction
testaction publish to github marketplace
name: Demo Greeting
on: [push, workflow_dispatch]

jobs:
  greet-user:
    runs-on: ubuntu-latest
    steps:
      - name: Greet with Demo Action
        uses: your-username/demo-actionlearner@v1
        with:
          user-name: 'John Doe'