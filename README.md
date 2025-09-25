## 👋 This is a repository containing sample slides for DSCI 100 using Quarto!

The purpose of this project is to gauge interest in converting DSCI 100 slides from Rise to Quarto.

Please take a look through these slides for "Inference 1" and compare them to the current RISE version.

## 💡 Features and Considerations

-   **Enhanced accessibility**: no more zooming in and out

<!-- -->

-   **Engagement through live coding**: students can code live in the lecture with you. Even if we load in data sets and manipulate them, we can do this "under the hood" in a hidden code chunk in Quarto. Students can still interact with them live in lecture (not being able to follow along has been a common complaint I've received this semester)
-   **Note-taking**: Quarto allows students to not only code live, but take notes in dedicated chunks IN the slides. That means everything is in one place. Students can save the slides easily as a PDF.

## 👩‍🏫 Viewing the Slides

Please clone this repository and open the Quarto Project in RStudio.

To test these slides, please;

1.  Install the `webr` extension in the terminal: `quarto add coatless/quarto-webr`

2.  Render the slides locally using `quarto render` in the terminal, or by opening the `.qmd` file and clicking the "Render" button.
