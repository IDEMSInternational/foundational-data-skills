# Foundational Data Skills

The purpose of this course is to introduce learners to data skills. Through practical activities, learners will explore, organise, clean, and visualise data.

## Course Structure

This course is built using [PreTeXt](https://pretextbook.org/) and contains 11 sections:

1. **Introduction to Data Analysis** - Fundamental concepts of data analysis
2. **Multilevel Data** - Understanding hierarchical data structures
3. **Exploring Data** - Techniques for initial data exploration
4. **Cleaning and Recoding Data** - Preparing data for analysis
5. **Visualising Multidimensional Data** - Visualising multiple variables
6. **Data Shapes** - Wide vs long format and reshaping data
7. **Handling Factors** - Working with categorical variables
8. **Missing Values** - Strategies for handling missing data
9. **Types of Variability** - Understanding sources of variation
10. **Measuring Variability** - Statistical measures of spread
11. **Accounting for Variability** - Drawing conclusions with uncertainty

## Building the Course

### Prerequisites

- Python 3.10 or higher
- PreTeXt CLI (`pip install pretext`)

### Build Commands

Build the web version:
```bash
pretext build web
```

View the course locally:
```bash
pretext view web
```

Build a PDF version:
```bash
pretext build print
```

Build all deployable targets:
```bash
pretext build --deploys
```

## Project Structure

```
├── project.ptx              # Project configuration
├── source/
│   ├── main.ptx             # Main course file
│   ├── docinfo.ptx          # Document metadata
│   ├── frontmatter.ptx      # Front matter
│   ├── sections/            # Course sections
│   │   ├── sec-introduction-to-data-analysis.ptx
│   │   ├── sec-multilevel-data.ptx
│   │   ├── sec-exploring-data.ptx
│   │   ├── sec-cleaning-and-recoding-data.ptx
│   │   ├── sec-visualising-multidimensional-data.ptx
│   │   ├── sec-data-shapes.ptx
│   │   ├── sec-handling-factors.ptx
│   │   ├── sec-missing-values.ptx
│   │   ├── sec-types-of-variability.ptx
│   │   ├── sec-measuring-variability.ptx
│   │   └── sec-accounting-for-variability.ptx
│   ├── activities/          # Course activities
│   └── notes/               # Course notes
└── publication/             # Publication settings
```

## Learning PreTeXt

See the [PreTeXt documentation](https://pretextbook.org/documentation.html) for links to a variety of resources.

We also recommend browsing through the [annotated sample article](https://pretextbook.org/examples/sample-article/annotated) and [annotated sample book](https://pretextbook.org/examples/sample-book/annotated/) if you want to find examples and see the PreTeXt source for those examples quickly.

## License

See [LICENSE](LICENSE) for details.
