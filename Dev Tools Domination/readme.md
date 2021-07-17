// Regular
    console.log("hi");
    // Interpolated

    console.log("hi %s",'guys');

    // Styled
    console.log("%c superman",'background:blue; color:white;')

    // warning!
    console.warn("oh no");

    // Error :|
    console.error("It's an error");

    // Info
    console.info("info");

    // Testing
    //console.assert(some statement, "what you wanna throw when it is wrong");
    
    // clearing
    //console.clear();

    // Viewing DOM Elements
    console.dir('p');

    // Grouping together
    dogs.forEach(dog=>{
      console.groupCollapsed(`${dog.name}`);
      console.log("hi doggie");
      console.groupEnd(`${dog.name}`);
    });

    https://github.com/soyaine/JavaScript30/tree/master/09%20-%20Dev%20Tools%20Domination