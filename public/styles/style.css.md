# Styles
```css
*{
  font-family: Arial, Helvetica, sans-serif;
}

body{
  display: flex;
  flex-direction: column;
  align-items: center;
  margin: 0;
  padding: 0;
}

a{
  text-decoration: none;
  font-weight: normal;
  color:CADETBLUE;
}

a:hover{
  font-weight: bold;
}

.links>a{
  padding: 10px;
}
form{
  display: flex;
  flex-direction: column;
  width: 40%;
  margin: 30px auto;
  min-width: 280px;
}

label input{
  margin: 5px;
  padding: 5px;
  font-size: 1em;
  width: 60%;
  margin-right: 15px;
}

form>label{
  margin: 5px;
  padding: 5px;
  font-size: 1em;
  width: 100%;
  display: flex;
  align-items: center;
  justify-content: space-between;

}

form>button{
  margin: 20px 5px;
  padding: 8px 5px;
  font-size: 1em;
  background-color: white;
  color: CADETBLUE;
  border: 2px solid CADETBLUE;
}

form>button:hover{
  background-color: CADETBLUE;
  color: white;
  cursor: pointer;
}
```