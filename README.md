# Plant Simulation AI Agent
## What is this?
This is an embed plant simulation AI agent help the user to auto generate plant simulation model.

## What need to use it?
You need the following prepared to use this tool.
* 1, Python (3.10 or higher) library installed in system level
* 2, Plant Simulation (with professional license) installed in your local machine
* 3, OpenRouter API key
* 4, Required Python libray in the requirement.txt

## How to use it?
* 1,  When you have everything prepared, new a blank plant simulation part.
* 2, Import this tool.psobj file into your model
* 3, In the AI_Agent dialog, input your OpenRouter API key.
* 4, Select the suitable AI model in the Dialog
* 5, Type your prompt in the prompt text box.
* 6, Select support files for your tasks
* 7, Click Run to wait the result


## Example Prompt:
* 1 create two stations and one assembly station and two source objects and one drain object and connect them each other. The model path is .Models.Model
![](./Example/Example1_prompt_demo.mp4)

* 2 Create a similar assebly line as shown in the picture, but with one more station in each of current existing pre-process branches before into the assembly station. The model path is .Models.Model
![](./Example/Example2_image_demo.mp4)

* 3, Create an assembly line from the upload xml file. The model path is .Models.Model
![](./Example/Example3_xml_demo.mp4)