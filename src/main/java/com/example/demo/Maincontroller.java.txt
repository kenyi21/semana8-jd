package com.example.demo;

import org.springframework.stereotype.Controller;
import org.springframework.web.bind.annotation.GetMapping;
import org.springframework.web.bind.annotation.ResponseBody;

@Controller
public class Maincontroller {
    

 @GetMapping (path = "/")  
public @ResponseBody String home(){
    return "hola semana 8";
}


}
