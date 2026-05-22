<div align="left"> 
     <h2><em>$whoami</em></span></h2> 
</div>

<br />

<div align="left">
     
```js
function aboutMe() {
	const info = {
		name: "Said",
		age: 20,
		isWorking: false,
		langs: ["Arabic", "English", "German"],
		description: "Aspiring software engineer :D",
		skills: ["javascript", "python", "php", "HTML", "CSS", "MongoDB", "MySQL", "Oracle DB", "Git"],
		wantToLearn: ["C++/C", "Rust", "React"],
		website: "cisc.dev",
	};
	const { name, age, isWorking, langs, description, skills, wantToLearn, website } = info;

	return `Hello my name is ${name} and i am ${age}!
    ${description.toUpperCase()}
    ${isWorking ? "Working in a project!" : "Not working in any current project!"}
    I speak 3 lanagauges :D, im fluent in ${langs[0]} AND ${langs[1]}, also im learning ${langs[2]}.
    SKILLS: [${skills.join(", ")}]
    LEARNING: [${wantToLearn.join(", ")}]
    WEBSITE: [${website}]`;
}

console.log(aboutMe());
```
</div>
