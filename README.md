StruProKGR: A Structural and Probabilistic Framework for Sparse Knowledge Graph Reasoning
=========================================================================================

This is the official code release of the following paper:

StruProKGR: A Structural and Probabilistic Framework for Sparse Knowledge Graph Reasoning

## Requirements

* Python3 (developed based on Python 3.8)

## Running the program

* For FB15K-237-10% dataset

  ```
  python StruProKGR.py --dataset FB15K-237-10 --test --max_num_programs 1000 --max_path_len 6 --max_path_branch 15 --diminishing_factor 0.5 --decay_factor 0.95 --name_of_run FB15K-237-10
  ```
* For FB15K-237-20% dataset

  ```
  python StruProKGR.py --dataset FB15K-237-20 --test --max_num_programs 500 --max_path_len 5 --max_path_branch 5 --diminishing_factor 0.5 --decay_factor 0.6 --name_of_run FB15K-237-20
  ```
* For FB15K-237-50% dataset

  ```
  python StruProKGR.py --dataset FB15K-237-50 --test --max_num_programs 100 --max_path_len 4 --max_path_branch 3 --diminishing_factor 0.5 --decay_factor 0.8 --name_of_run FB15K-237-50
  ```
* For NELL23K dataset

  ```
  python StruProKGR.py --dataset NELL23K --test --max_num_programs 100 --max_path_len 6 --max_path_branch 30 --diminishing_factor 0.5 --decay_factor 0.5 --name_of_run NELL23K
  ```
* For WD-singer dataset

  ```
  python StruProKGR.py --dataset WD-singer --test --max_num_programs 100 --max_path_len 6 --max_path_branch 30 --diminishing_factor 0.5 --decay_factor 0.2 --name_of_run WD-singer
  ```
