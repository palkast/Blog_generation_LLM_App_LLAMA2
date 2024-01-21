# Blog_generation_LLM_App_LLAMA2
This project is about end to end implementation of LLM model LLAMA2 developed by Meta from Hugging Face API using langchain and deployed on Stream Lit App.<br />

Llama2 - Meta is open source llm model.<br />This project will showcase generativeAI Solutions using Llama-2.<br />

Steps:<br />

1.Get acquainted with LLAMA2 model.<br />

   a)Selecting Llama-2<br />
     Among the various open-source Large Language Models (LLMs) such as Llama-2 by Meta, Alpaca, Vicuna, Falcon, and others, each with its own advantages and<br />
     drawbacks I've opted for Llama-2 by Meta in this project. It surpasses other open-source LLMs in multiple external benchmarks, including those related to reasoning, 
     coding proficiency, and knowledge tests. Llama-2 is available in three different sizes: 7B, 13B, and 70B parameters. This variety facilitates exploration with smaller 
     models and scalability to larger models based on specific use cases.To download Llama-2 model, first you need to fill in the request form at Meta website<br />.
     Additionally downloads are also provided through HuggingFace. However, first Meta request form should be filled with same email as HuggingFace account.<br /> 
     After doing so you can request access to any of the models on Hugging Face and within 1–2 days your account will be granted access to all versions.
     
    b)Choosing Quantized Model - Download LLAMA2 model from Hugging face which is less parametrized model : https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML<br />
    
2.Create virtual conda python environments (venv). Then activate the conda environment.<br />
3.Create requirements.txt file<br /> 
4.Coding - Create app.py (application program to call the model and get response and deploy on StreamLit app)<br />

  a)Create function To get response from LLAma 2 model<br />
  b)Initialize LLama2 model<br />
  c)Create Prompt Template<br />
  d)Generate the response from the LLama 2 model<br />
  e)Now set the page for StreamLit app front end<br /> 
  f)Create header and input area for the front end<br />
  g)Get response from llama2 model using  input parameters : input text , no_words,blog_style<br />
  g)Run the streamlit app using "streamlit run app.py"<br />
  h)Please click on the url generated to see the running Stremalit application.<br />
  i)Provide input like title of blog, blog style and no of words to get a blog as an output of the model.<br />

This is How the app on streamlit looks like :<br /> 

[![Picture1.png](https://i.postimg.cc/htQCN8Qy/Picture1.png)](https://postimg.cc/75DM22V0)

We can see, it provides the correct answer with great detail.<br />

Conclusion-
This is how Generative Ai solutions can be built using the following technologies :<br />

  * Llama2 Model: The core language model from Meta, providing state-of-the-art natural language processing capabilities.<br />

  * LangChain: Utilized for seamless integration and communication with the Llama2 model.<br />

  * Streamlit: is an open-source Python framework for machine learning and data science teams to create interactive data apps in minutes.<br />



