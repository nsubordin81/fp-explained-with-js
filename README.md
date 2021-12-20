# fp-explained-with-js
a set of example code that follows along the blog "What I wish someone had explained about functional programming" by James Sinclair, you can read it here: https://jrsinclair.com/articles/2019/what-i-wish-someone-had-explained-about-functional-programming/

# setup

To make the interactive notebooks with a javascript kernel run for this repository I leveraged images published by Cristian Prieto as referenced in their github repo docker-jupyter. To follow along yourself, go ahead and clone this repo and cd into it, then 

`docker pull cprieto/docker-jupyter`

will pull down the image that is already set up to run a jupyter notebook with a javascript kernel as a container process. then

`docker run -p 8888:8888 --rm -v $(pwd)/notebooks:/notebooks cprieto/jupyter-javascript` 

when run from the root of this cloned repository will start a container process using that image and also it will create a bind mount to the notebooks directory in the cloned repository on your host so the interactive notebooks are available to you for running and modification. 
