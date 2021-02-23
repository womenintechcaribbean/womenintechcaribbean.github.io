# Speaker Slate

People around the world are constantly looking to build a more diverse panel of speakers for their events, but they are having difficulty in finding said people who are willing to partake in them.

The Speaker Slate was created to showcase the amazing talent we have within our organization. This platform will allow speakers to be contacted directly to take part in talks and/or other public appearances.

> created & maintained by Sowmya Thottambeti

# How to Join?

### :sparkles: Step 1

Clone the repository on your local machine & create a feature branch locally


### :sparkles: Step 2

Navigate to the file, `speakers.json`. **Note:** This JSON file contains all the information pertaining to the various speakers

### :sparkles: Step 3 

Create an object for yourself with the following properties:

- **name** *(string)* -- your full name

- **bio** *(string)* -- short description of yourself. include education, years of experience etc. -- anything that may qualify you to give talks on certain topics. **Tip:** Adding `\n` before a character will start a new paragraph and adding `--` before a character will add a bullet point.

- **image** *(string)* -- path to your image. store your photo in the images/speakers directory with the file name as firstName_lastName. for example, `"/images/speakers/sowmya_thottambeti.jpg"`. this is _optional_, so if you don't want to add an image, put `null`

- **homeCountry** *(string)* -- the Caribbean country that you represent

- **currentLocation** *(string)* -- where you are currently located

- **currentPosition** *(string)* -- what you are currently doing 

- **category** *(array of string)* -- what topics would you like to talk about? what topics are you an expert in? use short phrases. e.g "Diversity & Inclusion" "React Native" "Journey into Tech" "Geospatial Science" "Non-technical talks" "Soft-skills" etc.

- **contact** *(object)*
	- **email** *(string)* -- email address || `null`
	- **linkedIn** *(string)* -- linkedIn username || `null`
	- **instagram** *(string)* -- instagram handle || `null`
	- **twitter** *(string)* -- twitter handle or null || `null`

- **speakingExperience** *(string)* -- single word describing your speaking experience

- **description** *(string)* -- short description of your speaking experience, if any. otherwise, put `null`. **Tip:** Adding `\n` before a character will start a new paragraph and adding `--` before a character will add a bullet point.

- **links** *(array of string)* -- share any relevant urls to past talks, if any. otherwise, put `null`. don't just copy the url directly from the browser but instead, use the condensed url provided (if available) when sharing the content.

- **appearances** *(array of string)* -- what type of appearances are you willing to partake in?

### :sparkles: Step 4 

Upon completion, commit the changes to your local feature branch, push the code to your remote feature branch and then, create a pull request against the main branch. The title of the pull request should be "Submission for firstName lastName".


### :sparkles: Step 5

The product owner will review the pull request & if everything looks good, congrats -- you've made it to the speaker slate :tada:
