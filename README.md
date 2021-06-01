### Hi there 👋


I’m Shoaib Dar, a detail-oriented and analytical Full Stack Developer who loves to solve problems and puzzles. I enjoy reading, traveling, and learning about the world we live in, and have open-minded conversations with the people in it. Growing up, I have been helped immensely by my community through difficult times and I can't wait to start my career so I can repay back my community one day. I am currently in Pursuit's intensive 12-month long software engineering fellowship program, progressing through six modules:

## Module 1:  JavaScript

```javascript
const nextInLine = (queue, newPerson) => {
  queue.push(newPerson);
  let oldPerson = queue.shift();
  return oldPerson; 
}
```

## Module 2: HTML & CSS
```
<body>
  <p> Hello World</p>
</body>
```
```
body{
display: flex;
justify-content: center;
}
```
![Checkmark](https://webstockreview.net/images/checkmark-clipart-green-5.png)



## Module 3: REACT

```
const Home = (props) => {
    const [name, setName] = useState('');
    const [people, setPeople] = useState([]);
    
    const handleName = (e) => setName(e.target.value);

    const retrievePeople = async () => {
        try {   const { data } = await axios.get("/api/people");
                setPeople(data)
        } catch (error) {
            setPeople([])  }
    }

    useEffect(() => retrievePeople(), [])

    return (<section className="home-container">
                  <label >Name:
                <input type='text' size="40" value={name} onChange={handleName} required />
                    </label>
                    <section className="people-list">
                {people.map(person => <ListItem  personName={person.name} key={person.id} id={person.id}  />)}
                    </section>
            </section>)
}         
```

## Module 4: Full Stack: PERK-Stack Postgres, Express, React, Knex.js

```
In progress...
```
