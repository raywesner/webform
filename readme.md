# Drupal container info

The code in this repo creates a custom Drupal 10 container with a set of required libraries/modules for the securecloudforms.com website.

## building instructions

clone this repo, and run the following command

```bash
docker build -t drupal .
```

The code will need to be pushed into ECR.  If you login to the AWS console, and go to Elastic Container Registry, there is a button that says `View Push Commands` in the top right corner of the drupal repository.  Press that button, and follow the steps.  Note you will need your local AWS CLI configured correctly to proceed.