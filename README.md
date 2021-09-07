# CobaltStrike-TLS-Metadata-Analysis

As we have observed surge in use of Cobalt Strike, I did analysis of TLS certificates use by CS.
For this I use malicious PCAP's shared by Brad Duncan having Cobalt Strike usage (https://www.malware-traffic-analysis.net/).
For comparing how this metadata looks I fetched certificates from known good website while running Wireshark in the background.
I have attached herewith Metadata of certificates use by Cobalt Strike and also of Good websites.
If you are doing hunting in PCAP this data will surely give you starting point for investigation.
eg. x509sat.CountryName == ""

