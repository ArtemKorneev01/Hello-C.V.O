using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class HelloWorld : MonoBehaviour
{
    public bool isPrint = true; // проверка должна ли писать команда переменную wh    
    public string wh; // строчные данные       
    public int mount; // числовые данные
    private void Start()
    {
        // число = 2
        print(mount);
    }
    private void Update()
    {
        if (isPrint) // усли isPrint = истинна то:
        
        {
            
            // команда напишет hello world
            print(wh);
            isPrint = false;
        }
    }
}
