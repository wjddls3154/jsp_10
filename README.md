# jsp_10 : 변수 안의 내용 출력하기

![image](https://user-images.githubusercontent.com/37132897/158111898-e7b7e1ca-45a6-4abb-b990-28230f891647.png)

// 변수

        var person = {

                name: {
        
                firstname: "inkyo",
          
                lastname: "jung"
          
                },
        
                age: 25,
        
                married: false,
        
                };
      
      document.write(person["name"]); // 1. person 안의, name 을 출력했을 때, [object Object] 출력
      
      document.write("<br>");
      
      document.write(person["name"]["firstname"]); // 2. person 안의, name 안의, firstname 인 inkyo 출력
      
      document.write("<br>");
      
      document.write(person["name"]["lastname"]); // 3. person 안의, name 안의, lastname 인 jung 출력
      
      document.write("<br>");
      
      document.write(person["age"]); // 4. person 안의 age, 25 출력
      
      document.write("<br>");

