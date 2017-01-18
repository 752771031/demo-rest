# demo-rest
package com.libotao;
import org.springframework.boot.SpringApplication;
import org.springframework.boot.autoconfigure.EnableAutoConfiguration;
import org.springframework.web.bind.annotation.PathVariable;
import org.springframework.web.bind.annotation.RequestMapping;
import org.springframework.web.bind.annotation.RequestMethod;
import org.springframework.web.bind.annotation.ResponseBody;
import org.springframework.web.bind.annotation.RestController;

  @RestController
@EnableAutoConfiguration
public class usercontroller {

    @RequestMapping
    @ResponseBody
    public String hello(){
        return "hello" ;
    }
    public static void main(String[] args) throws Exception {
        SpringApplication.run(usercontroller.class, args);
    }
}


package com.libotao;
import org.springframework.boot.SpringApplication;
import org.springframework.boot.autoconfigure.SpringBootApplication;

@SpringBootApplication
public class useappliedcation {

	public static void main(String[] args) {
		SpringApplication.run(useappliedcation.class, args);
	}
}



package com.libotao;

public class demo {
   private int id;
   private String name;
public int getId() {
	return id;
}
public void setId(int id) {
	this.id = id;
}
public String getName() {
	return name;
}
public void setName(String name) {
	this.name = name;
}
   
   }
   

