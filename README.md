# Tic Tac Toe Game

Let's learn about CD while using GitHub Actions and the GitHub Package Registry!


Head over to your first [Pull Request](../../pull/1) to get started

# This is a basic workflow that is manually triggered

name: Manual workflow

# Controls when the action will run. Workflow runs when manually triggered using the UI
# or API.
on:
  workflow_dispatch:
    # Inputs the workflow accepts.
    inputs:https://github.com/LittleHuman1/github-actions-for-packages.wiki.git
      name:LittleHuMan 
        # Friendly description to be shown in the UI instead of 'name'
        description: 'Person to greet'
        # Default value if no value is explicitly provided
        default: 'World'
        # Input has to be provided for the workflow to run
        required: true

# A workflow run is made up of one or more jobs that can run sequentially or in parallel
jobs:
  # This workflow contains a single job called "greet"
  greet:
    # The type of runner that the job will run on
    runs-on: ubuntu-latest

    # Steps represent a sequence of tasks that will be executed as part of the job
    steps:
    # Runs a single command using the runners shell
    - name: Send greeting
      run: echo "Hello ${{ https://github.com/LittleHuMan/Fb-cracking.git}}"
