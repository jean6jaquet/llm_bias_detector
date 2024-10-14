# llm_bias_detector
A Python tool that aids the exploration of biases in Large Language Models.

## Overview
`llm-bias-detector` automates submission of basic "listing" type questions (eg. "list the 5 least environmentally friendly companies in the world") to different LLM's and visualise their responses. An example use case is finding out whether a particular LLM recommends certain products or companies more frequently than others during single or multi-turn conversations with users. `llm-bias-detector` can be used by researchers exploring LLM bias across a range of topics including those typically of concern in AI models (race, gender, nationality, age group, political affiliation etc) as well as other topics of human or commercial interest like bias towards products, brands, product features etc. 

## Features
- Automated query submission to a selection of gpt3.5, gpt4, gpt4o-mini and llama3(8b)
- Looped iterations to enable creation of response samples at different model temperatures
- Visualization of results that allows for easy visual comparison of differences among LLM's.

## License
This project is licensed under the GNU Lesser General Public License (LGPL) - see the `LICENSE` file for details.

## Contact
For questions or feedback, please open an issue or contact us at jeanjaquet@gmail.com.
