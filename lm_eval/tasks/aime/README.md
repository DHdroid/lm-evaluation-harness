# AIME

## Paper
[Measuring Mathematical Problem Solving With the MATH Dataset](https://arxiv.org/abs/2103.03874)

[Homepage](https://www.kaggle.com/datasets/hemishveeraboina/aime-problem-set-1983-2024)

### Citation

```text
@misc{hendrycks2021measuringmathematicalproblemsolving,
      title={Measuring Mathematical Problem Solving With the MATH Dataset}, 
      author={Dan Hendrycks and Collin Burns and Saurav Kadavath and Akul Arora and Steven Basart and Eric Tang and Dawn Song and Jacob Steinhardt},
      year={2021},
      eprint={2103.03874},
      archivePrefix={arXiv},
      primaryClass={cs.LG},
      url={https://arxiv.org/abs/2103.03874}, 
}

@dataset{aime_1983_2024,
  author = {Hemish Veeraboina},
  title = {AIME Problem Set 1983-2024},
  year = {2023},
  publisher = {Kaggle},
  url = {https://www.kaggle.com/datasets/hemishveeraboina/aime-problem-set-1983-2024}
}
```

### Groups, Tags, and Tasks

#### Groups

* `math_word_problems`

#### Tasks

* `aime`: 

### Checklist

For adding novel benchmarks/datasets to the library:

* [x] Is the task an existing benchmark in the literature?
  * [x] Have you referenced the original paper that introduced the task?
  * [ ] If yes, does the original paper provide a reference implementation? If so, have you checked against the reference implementation and documented how to run such a test?

If other tasks on this dataset are already supported:

* [ ] Is the "Main" variant of this task clearly denoted?
* [ ] Have you provided a short sentence in a README on what each new variant adds / evaluates?
* [ ] Have you noted which, if any, published evaluation setups are matched by this variant?
