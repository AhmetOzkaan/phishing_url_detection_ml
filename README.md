# Phishing URL Detection Project

Beginner ML Project for Aygaz ML Bootcamp


## Project URL

Kaggle Notebook: https://www.kaggle.com/code/ahmetozkaan/phishing-url-detection

## Project Overview

This project aims to classify URLs as either phishing or legitimate using machine learning techniques. The dataset used contains various features related to URLs, which help in identifying suspicious patterns. The K-Nearest Neighbors (KNeighborsClassifier) algorithm was employed as a supervised learning method, while the Isolation Forest algorithm was used for unsupervised anomaly detection.

## Dataset Description

The dataset contains 2,500,000 URLs and various features associated with them. 
Here is the updated **Dataset Description** section based on the provided format:

| #  | Column Name           | Feature Description                                           | Data Type |
|----|-----------------------|---------------------------------------------------------------|-----------|
| 1  | url                   | URL string                                                    | str       |
| 2  | source                | Source of the URL (phishing URLs or URL ranking databases)     | str       |
| 3  | label                 | Category of the URL (either phishing or legitimate)            | str       |
| 4  | url_length            | Length of the URL in characters                               | int       |
| 5  | starts_with_ip        | Does the URL start with an IP address?                        | bool      |
| 6  | url_entropy           | Entropy of the URL/hostname (measuring randomness)            | float     |
| 7  | has_punycode          | Does the URL contain Punycode characters?                     | bool      |
| 8  | digit_letter_ratio    | Ratio of digits to letters in the URL                         | float     |
| 9  | dot_count             | Count of occurrences of the dot (.) character in the URL      | int       |
| 10 | at_count              | Count of occurrences of the at (@) character in the URL       | int       |
| 11 | dash_count            | Count of occurrences of the dash (-) character in the URL     | int       |
| 12 | tld_count             | Does the URL's subdirectory contain top-level domains (TLDs)? | int       |
| 13 | domain_has_digits     | Does the base domain contain digits?                          | bool      |
| 14 | subdomain_count       | Number of subdomains in the base URL                          | int       |
| 15 | nan_char_entropy      | Entropy of non-alphanumeric characters in the URL             | float     |
| 16 | has_internal_links    | Does the URL contain internal links?                          | bool      |
| 17 | whois_data            | WHOIS record of the domain                                    | bool      |
| 18 | domain_age_days       | Age of the domain in days (extracted from WHOIS data)         | float     |
