# py-beam-dataflow-pipeline

## 🚧 This project is under construction! 🚧

This project contains a Apache Beam pipeline, written using the [Python SDK](https://beam.apache.org/documentation/sdks/python/).

It consumes data from [Google PubSub](https://cloud.google.com/pubsub/docs/overview) using the built-in [PubSub I/O connector](https://beam.apache.org/releases/pydoc/current/apache_beam.io.gcp.pubsub.html), transforms it and pushes it back to [Google BigQuery](https://cloud.google.com/bigquery). To accomplish this, the [BigQuery I/O connector](https://beam.apache.org/releases/pydoc/current/apache_beam.io.gcp.bigquery.html) by Apache Beam is used.

The data that is streamed into PubSub comes from my [IoT sensor mock](https://github.com/torbendury/py-iot-temp-mock) which can be deployed as a [Google Cloud Function](https://cloud.google.com/functions) with a one-liner.

## Authors

- [@torbendury](https://www.github.com/torbendury)

## Contributing

Contributions are always welcome!

Open a GitHub issue (and, if you want, a PR) and describe what you would like this project to become.

## License

This project is published under [Apache 2.0](LICENSE).
