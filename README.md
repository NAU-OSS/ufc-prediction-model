# UFC Prediction Model

## Description

This project is a UFC prediction model that uses fighter statistics to predict the winner of each matchup on a UFC card. The model uses a point-based system that looks at different statistics such as reach, recent activity, takedown defense, striking numbers, and other fighter information.

One of the main ideas behind this project is that the model is meant to improve over time. After each UFC event, the actual results are compared to the predictions. The results are then analyzed to see where the prediction system may have been wrong. Based on that analysis, the scoring system and statistics can be adjusted before the next UFC event. This creates a cycle where the model can be tested, evaluated, and updated over time.

## Installation

To use the project, clone the repository to your computer:

```bash
git clone https://github.com/NAU-OSS/ufc-prediction-model.git
cd ufc-prediction-model
```

Make sure Python is installed on your computer. The project may also require additional Python packages depending on the version of the model being used.

## Usage

The model uses a CSV file containing information about the fighters on a UFC card. The CSV should contain the fighter names and the statistics used by the prediction system.

After providing the CSV file, run the prediction program. The model processes the fighter statistics and assigns points to each fighter based on the current scoring system. The fighter with the higher score is then selected as the predicted winner.

A basic workflow looks like this:

1. Collect fighter statistics for an upcoming UFC card.
2. Put the information into the required CSV format.
3. Run the prediction model.
4. Review the predicted winners.
5. Compare the predictions with the actual results after the event.
6. Analyze mistakes and update the scoring system when needed.
7. Use the updated model for the next UFC card.

## Project Status

This project is currently under development. The prediction system is still being tested and adjusted as more UFC events are processed. The goal is to continuously test the model and make improvements based on its results.

## Roadmap

Future improvements may include:

* Adding more fighter statistics to the model.
* Improving how recent fights are weighted.
* Testing different scoring methods.
* Automating the process of collecting fighter statistics.
* Improving the CSV input process.
* Tracking prediction accuracy over time.
* Comparing different versions of the prediction model.
* Continuing to analyze incorrect predictions and use those results to improve the model.

## Contributing

Contributions and suggestions are welcome. If you have an idea for improving the prediction system, you can open an issue or submit a pull request with your proposed changes.

## Contact

The project is maintained by Brad Chernauskas.

GitHub: https://github.com/Bradcher

Project Repository: https://github.com/NAU-OSS/ufc-prediction-model

## License

This project is licensed under the MIT License. See the `license.md` file for the full license.
