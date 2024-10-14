# Interface
![Screenshot from 2024-10-15 00-37-13](https://github.com/user-attachments/assets/81ca4ef8-23e8-422e-a4db-b63b35372709)


# hpc-project
Distributed HyperParameter Tuning using HPC

# Instructions to run a node

## Change dir after cloning
```cd slave```

## Build the docker
```docker build . -t hpc-slave```

## Run the docker container
```docker run hpc-slave --rm ```

## Kill running nodes 
```docker container kill $(docker ps -q)```
