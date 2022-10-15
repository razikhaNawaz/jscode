const person={

    firstName:'razikha',

    lastName:'parveen',

    age:'30',

    hobbies:['music','movies','sports'],

    addres:{

        street:'50 main street',

        city:'bangalore',

        state:'Karnataka',

    }

}

console.log(person);

console.log(person.hobbies[1]);

console.log(person.addres.state);

console.log(age);

const{firstName,lastName,Age}=person

console.log(age);

const{address:{state}}=person

console.log(state);



const todos=[

    {
    id: 1,
    text: 'take out trash',
    isCompleted: true
},
{
    id: 2,
    text: 'attend meeting',
    isCompleted: true
},
{
    id: 3,
    text: 'doctor appointment',
    isCompleted: false
},
];
const todosJSON=JSON.stringify(todos);
console.log(todosJSON);
for(let i=0;i<todos.length;i++){
   console.log(todos[i].id);
}
let i=0;
while(todos.length){
    console.log(todos[i].id);
    i++;
}
for(let todo of todos){
    console.log(todo.text);
}

final copy
