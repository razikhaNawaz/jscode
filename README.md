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
