# Long Beach Pet Shelter Analysis

For a Fall 2025 team data science project at UC San Diego, we cleaned and analyzed 34,468 Long Beach animal shelter records from 2016 to 2025. We used exploratory data analysis and predictive modeling to examine how characteristics such as age, species, and spay/neuter status relate to whether cats and dogs are adopted and how long adoption takes.

## Research Question

How do animal characteristics and listing features influence the likelihood and speed of adoption for cats and dogs in Long Beach?

## Features of Interest

- **Animal characteristics:** Species, age, sex, size, breed, coat color, and spay/neuter status.
- **Behavioral traits:** House-training and compatibility with dogs, cats, and children.
- **Listing features:** Distance, number of photos, and publication date.

## Analysis

- **Species, age, and sex:** Dogs had a higher adoption rate than cats (62% vs. 34%). Senior animals had the highest observed adoption rate, contrary to our initial hypothesis. Adoption rates were similar for males and females.
- **Spay/neuter status and intake condition:** Spayed or neutered animals had a 67% adoption rate, compared with 26% for unsterilized animals. Animals recorded as feral, severely ill, or underweight at intake had some of the lowest adoption rates.
- **Linear regression:** We used a multivariable linear regression model to estimate how each feature was associated with adoption likelihood while accounting for the other features in the model. Intake condition and intake type showed the strongest associations, and spay/neuter status was also an important predictor. The “Intake Exam” category had the largest positive coefficient, while “Feral” and “Fractious” had large negative coefficients. Age and sex showed weaker associations after accounting for the other variables.

## Project Notebook

See the [final project notebook](03-FinalProject.ipynb) for the full report, including visualizations, linear regression results, and conclusions.## Project Notebook