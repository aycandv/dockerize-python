# dockerize-python

Aim of this repository is to eliminate any incompatibilities between Python packages and operating systems. Python scripts located in folder `scripts` can be run. You can modify `requirements.txt` file according to your needs.

## How to Run

After clonning the repository, execute following command to run `sample1.py` script:

```
docker-compose run --rm py-engine python sample1.py
```