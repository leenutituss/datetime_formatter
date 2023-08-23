# Datetime Format Converter
  This is a Python script that converts a date in the format "YYYY/MM/DD" to a desired formatted string.
## Usage
  You can use the `datetime_format_converter` function to convert a date in the "YYYY/MM/DD" format to a more readable format. The function takes the input date as a string argument and prints the result.
## Code
  import datetime
  def datetime_format_converter(input):
    datetime_input = datetime.datetime.strptime(input, "%Y/%m/%d")
    desired_format_converter = datetime_input.strftime("%A, %Y %b %d")
    print(desired_format_converter)
datetime_format_converter("2023/3/11")
