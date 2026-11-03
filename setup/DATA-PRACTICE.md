# Harmless data-analysis practice
This tiny dataset is invented solely to test your tools. It represents a fictional temperature sensor, not a UAV test. It is not mission evidence and gives no mission answer.

File: [practice-sensor.csv](practice-sensor.csv). Version: PRACTICE-1.
There are three columns: sample_id (row identifier), time_s (seconds), temperature_C (degrees Celsius). There are six observations, plus one header row; no missing values.

## Try this before checking the expected result
Ask your AI:
> Open setup/practice-sensor.csv in my fork at [URL]. State the actual file or upload used. Count data rows excluding the header, list the column names and units, calculate the mean temperature, and make a scatter/line plot of temperature_C against time_s with labeled units. Show your calculation or analysis code and any access limitations. Do not substitute invented data or change my repository.

Reading a text file does not guarantee that your AI's analysis tool has the CSV available. If it cannot load the complete data or produce a plot, use the upload route below. A description of a plot is not a rendered plot.

## Manually checkable results
- Six data rows, P01 through P06.
- Mean: (20 + 22 + 24 + 26 + 28 + 30) / 6 = 25 degrees Celsius.
- Plot: six points at (0,20), (10,22), (20,24), (30,26), (40,28), (50,30).
- Horizontal axis: time in seconds; vertical axis: temperature in degrees Celsius.
- The straight increase is a feature of this invented practice file, not evidence about the mission.
Inspect at least the first and last plotted points and check the mean yourself. Do not mark access verified solely because the AI repeats these expected results.

## File-upload fallback
1. Open practice-sensor.csv in your own fork using GitHub.
2. Use the raw-file download control to save the CSV, not the GitHub HTML page. Open the saved file and confirm the header and six observations.
3. Attach that CSV to a chat with data-analysis/file-upload capability. Repeat the prompt, referring to the attached file instead of repository access.
4. Confirm the rendered plot and calculation. Record that upload worked but connector analysis did not, if applicable.
5. If uploads or analysis are unavailable, use a spreadsheet to make the same calculation and plot, or arrange a partner/instructor demonstration. Report this before class; no paid upgrade is required.

Do not upload credentials, private records, or unreleased files. This practice is not an assessed mission response.
