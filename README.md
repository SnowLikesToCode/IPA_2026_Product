# IPA 2026 Product - Elastic Development Config

This repository contains the local Elasticsearch and Kibana configuration used for the IPA product development environment in WSL.

## Included Files

- `configs/elasticsearch.yml` - local single-node Elasticsearch configuration
- `configs/kibana.yml` - local Kibana configuration connected to Elasticsearch on `127.0.0.1:9200`
- `.gitignore` - excludes runtime data, logs, keystores, certificates and local secrets

## Local Services

The local development setup uses:

- Elasticsearch on `http://127.0.0.1:9200`
- Kibana on `http://127.0.0.1:5601`
- Single-node Elasticsearch discovery
- Security disabled for local development testing

## Notes

These files are meant for the local IPA development environment only. They do not include Elasticsearch data directories, logs, keystores, certificates or API credentials.
