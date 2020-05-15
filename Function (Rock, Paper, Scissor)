# Paper-Scissor-Rock (JS)

let userName = 'PUT YOUR NAME HERE';

const getUserChoice = userInput => {
  userInput = userInput.toLowerCase();
  switch (userInput) { 
    case 'rock':
      return userInput;
      break;
    case 'scissor':
      return userInput;
      break;
    case 'paper':
      return userInput;
      break;
    default:
      console.log(`DUDE?? BRO, really? never played PAPER-SCISSOR-ROCK before? Try again ${userName}..`);
  };
}

const getComputerChoice = (num) => {
  num = Math.floor(Math.random() * 3);
  switch (num) {
      case 0:
        return 'rock';
        break;
      case 1:
        return 'scissor';
        break;
      case 2:
        return 'paper';
        break;
  };
};

const determineWinner = (userChoice, computerChoice) => {
  if(userChoice === computerChoice) {
   return 'It\'s a T.I.E!';
  };
  if(userChoice === 'rock') {
    if(computerChoice === 'paper') {
      return 'Mr. Computer WON!!!';
    } else {
      return `Congrats ${userName}!! You won!!`;
    };
  };
  if(userChoice === 'scissor') {
    if(computerChoice === 'rock') {
      return 'Mr. Computer WON!!!';
    } else {
      return 'Congratulation, you beat Mr. Comp!!';
    };
  };
  if(userChoice === 'paper') {
    if(computerChoice === 'scissor') {
      return 'Mr. Computer WON!!!';
    } else {
      return `DUDE, ${userName}, you won!!!!`;
    };
  };
};


const playGame = () => {
  const userChoice = getUserChoice('Rock');
  const computerChoice = getComputerChoice();
  console.log('You threw: ' + userChoice);
  console.log('Mr Computer threw: ' + computerChoice);
  console.log(determineWinner(userChoice, computerChoice));
};

playGame();
