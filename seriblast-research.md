# Privacy Policy — Seriblast Research

**Last updated:** May 18, 2026
**Effective date:** May 18, 2026

Seriblast ("we", "us", "our") operates the Seriblast Research application (the "App"), an internal research tool used to analyze publicly available visual content for market trend research. This Privacy Policy explains what data the App processes and how.

## 1. Who we are

- **Operator:** Seriblast (independent operation by Byron Huerta)
- **Contact:** byron.huerta.urrea@gmail.com
- **Purpose of the App:** internal research and market trend analysis. The App is **not** a consumer product and is not offered to end users.

## 2. What the App does

The App connects to public APIs (such as the Pinterest API, Dribbble API, and similar developer platforms) using credentials we have registered ourselves. It retrieves publicly available content (such as pin metadata, image URLs, and shot descriptions) for the purpose of:

- Generating image embeddings for visual clustering and trend detection.
- Producing aggregated, anonymized analysis of design and packaging trends.

The App does **not** authenticate end users, does **not** request access to private user accounts, and does **not** post, modify, or interact with content on behalf of any user other than its own developer account.

## 3. Data we collect

The App processes only publicly accessible content returned by the third-party APIs we connect to. Specifically:

- Public image URLs
- Public pin/shot titles and descriptions
- Public board names and author usernames (when included in the public API response)

We do **not** collect:

- Email addresses or contact information of any end user
- Login credentials of any third party
- Private messages, private boards, or private collections
- Payment information
- Location data
- Cookies from end users

## 4. How we use the data

The retrieved content is processed locally to:

1. Compute machine-learning embeddings (using models such as CLIP) on image content.
2. Apply unsupervised clustering algorithms (such as HDBSCAN) to identify visual patterns.
3. Produce aggregated reports about design and packaging trends.

These reports describe **patterns at the population level** (e.g. "60% of mezcal packaging in this sample uses kraft labels"). They do not single out any individual user, account, or piece of content.

## 5. How we store the data

- All data is stored **locally** on the operator's own computer.
- Image files and embeddings are stored under password-protected user accounts on the operator's local file system.
- No data is shared with third parties.
- No data is uploaded to cloud services, public repositories, or other external destinations.

## 6. Data retention

We retain raw image downloads only as long as needed to compute embeddings (typically days). Aggregated reports and embeddings may be kept indefinitely for longitudinal trend research. Any individual user's content can be removed from our local cache upon written request to the contact email above.

## 7. Sharing

We do **not** share, sell, rent, or otherwise transfer any data obtained through the App to third parties. The aggregated trend reports we produce may be published or used internally by Seriblast, but they contain no identifying information about individual users or pieces of content.

## 8. Compliance with third-party platform terms

We use third-party APIs strictly within the terms of service of each platform (Pinterest, Dribbble, etc.). We respect rate limits, do not scrape outside the official APIs, and do not attempt to circumvent platform access controls.

## 9. Children's privacy

The App is not directed at children and we do not knowingly process any content from accounts identified as belonging to minors.

## 10. Your rights

If any third-party user identifies content they have posted on a public platform that has been processed by our App and wishes for it to be excluded from our local cache or future processing, they may write to the contact email above and we will honor the request within 30 days.

## 11. Changes to this policy

We may update this policy from time to time. The "Last updated" date at the top of this document reflects the latest revision. Material changes will be noted in the body of the document.

## 12. Contact

For any privacy-related question, contact: **byron.huerta.urrea@gmail.com**
