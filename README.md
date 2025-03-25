# Section-3

Task: A SOC team wants to automate threat intelligence ingestion from TorProject (or similar) and
cross-check the data against a firewall’s blocked IPs list.

Requirements:
* Write a Python script that:
   * Fetch a current list of Tor Exit Nodes (any source e.g. TorProject)
   * Compares them against a simulated firewall blocked list (provided as a JSON file).
   * Outputs a list of new threats that need to be blocked.
   * Write the Output to a SQLite Database
   * Write a python script that extracts the data from the SQL lite Database and exports the data to json format
* Uses environment variables with a configuration file for API credentials
* Provide the JSON file and Python Code as evidence
