#Elena Nikonova

###Contacts
* **Telegram:** *@elenaniksy*
* **Phone:** *+7911-157-60-36*

###Summary
I'm enthusiastic and self-motivated person with an extensive experience of 5 plus years in Web
 Marketing and Web Design. I have strong background in layout, typography and web design. 

I'm fond of web design, developing and self-development.
Capable of working in a team or independently. I wish to start my career as Junior Web Developer next year.

###Skills
* Html;
* CSS/Sass;
* Javascript/React;
* Git;
* Bootstrap;
* Photoshop/Illustrator/InDesign;
* Figma.

###Code Examples
```
<!--Javascript Example. This function receive a string and convert every first letter of the word in the string to Upper
 Case-->

function titleCase(str) {
const allLowerCase = str.toLowerCase();
const regex = /^(\w)|(\s\w)/ig;
const result = allLowerCase.replace(regex, str => str.toUpperCase());

return result;
}

<!--React example. This React class represent oldschool game "Magic Ball"-->

class MagicEightBall extends React.Component {
  constructor(props) {
    super(props);
    this.state = {
      userInput: '',
      randomIndex: ''
    }
    this.ask = this.ask.bind(this);
    this.handleChange = this.handleChange.bind(this);
  }
  ask() {
    if (this.state.userInput) {
      this.setState({
        randomIndex: Math.floor(Math.random() * 20),
        userInput: ''
      });
    }
  }
  handleChange(event) {
    this.setState({
      userInput: event.target.value
    });
  }
  render() {
    const possibleAnswers = [
      'It is certain',
      'It is decidedly so',
      'Without a doubt',
      'Yes, definitely',
      'You may rely on it',
      'As I see it, yes',
      'Outlook good',
      'Yes',
      'Signs point to yes',
      'Reply hazy try again',
      'Ask again later',
      'Better not tell you now',
      'Cannot predict now',
      'Concentrate and ask again',
      'Don\'t count on it',
      'My reply is no',
      'My sources say no',
      'Most likely',
      'Outlook not so good',
      'Very doubtful'
    ];
    const answer = possibleAnswers[this.state.randomIndex]
    return (
      <div>
        <input
          type="text"
          value={this.state.userInput}
          onChange={this.handleChange}
          style={inputStyle} /><br />
        <button onClick={this.ask}>
          Ask the Magic Eight Ball!
        </button><br />
        <h3>Answer:</h3>
        <p>
          {answer}
        </p>
      </div>
    );
  }
};
```

###Experience
I have some experience in educational projects.
You can find some of them [here](https://codepen.io/collection/ArGYkQ?cursor=ZD0xJm89MSZwPTEmdj0z) 

###Education
I have University Degree in Publishing (Books Layout Designer). I'm self-studying in IT sphere.
 * FreeCodeCamp. Responsive Web Design/ Javascript Algorithms and Data Structures/ Front-end Libraries.
 * Netology. Basic HTML and CSS courses.
 * Coursera. Web Development: Web Design and Javascript.

###Languages
* **English:** B1 
* **German:** A2. 
*Ich habe keine Sprachuebung seit 5 Jahren.*
