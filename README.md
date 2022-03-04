# Slack-Export-JSON-to-CSV

Convert Slack messages exported in their complicated JSON format to a simple CSV format.

## Usage

To run the application use the following command

```shell
python slack_json_to_csv.py folder_of_channel_to_export path_to_slack_users.json path_to_output_slack_messages.csv

```

## Example

```shell
python slack_json_to_csv.py slack_export/channelA slack_export/users.json output.csv
```

## License

This project is in the public domain and licensed with [The Unlicense](LICENSE)
