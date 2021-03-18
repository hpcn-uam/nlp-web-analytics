# NLP techniques applied to web analytics

Repository of our paper entitled "Natural Language Processing for Web Browsing Analytics: Challenges, Lessons Learned, and Opportunities" submitted to Computer Networks

Authors: Daniel Perdices, Javier Ramos, José Luis García-Dorado, Iván González and Jorge E. López de Vergara.

## Contents of the repository

- `dataset/` contains the datasets analyzed in the paper. 
    - `top100/` has samples obtained with five diferents User-Agents (U1, ..., U5) of the top 100 domains of Alexa.
    - `top2500/` has samples of the top 2500 domains of Alexa.

    Filenames follow the next syntax:
    ```
    <date>_<browser>.txt
    ```
    and their content is the analysis of the DNS packets. In particular, each line is:
    ```
    <timestamp> <counter of the number of responses in DNS packet> <question> <answer (only different from question in CNAME responses)> <TTL>
    ```

- `examples/` contains some examples of the methods. Soon to appear.

