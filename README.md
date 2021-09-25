# Assignments
Skip to content
surajs18
/
Java-Assignment-1-Day-1-Batch3
Public
Code
Issues
Pull requests
Actions
Projects
Wiki
Security
Insights
Java-Assignment-1-Day-1-Batch3/Assignment1.html
@surajs18
surajs18 Assignment 1 Day 1
 1 contributor
41 lines (36 sloc)  705 Bytes
<!DOCTYPE html>
<html>

<body>
    <div class="main">
        <ul class="ul">
            <li>A</li>
            <li>B</li>
            <li>C</li>
            <li>D</li>
            <li>E</li>
        </ul>
    </div>
</body>

</html>
<style>
    * {
        margin: 0;
        padding: 0;
    }
    
    .main {
        background-color: grey;
    }
    
    .ul {
        list-style-type: none;
        display: flex;
        justify-content: space-around;
        color: aliceblue;
    }
    
    @media(max-width: 480px) {
        .ul {
            flex-direction: column;
            flex-wrap: wrap;
            align-content: center;
        }
    }
</style>
