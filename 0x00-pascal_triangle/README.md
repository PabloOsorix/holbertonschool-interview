0x00. Pascal's Triangle
=======================

This repo is included in Specializations - Web Stack programming ― Back-end Course of Holberton School. We will cover the `Pascal´s triangle` for interview folder.

![Logo](https://www.howtogeek.com/wp-content/uploads/2021/05/laptop-with-terminal-big.png?height=200p&trim=2,2,2,50)

Tasks
-----

### 0\. Pascal's Triangle

Create a function `def pascal_triangle(n):` that returns a list of lists of integers representing the Pascal’s triangle of `n`:

*   Returns an empty list if `n <= 0`
*   You can assume `n` will be always an integer

```

    guillaume@ubuntu:~/0x00$ cat 0-main.py
    #!/usr/bin/python3
    """
    0-main
    """
    pascal_triangle = __import__('0-pascal_triangle').pascal_triangle
    
    def print_triangle(triangle):
        """
        Print the triangle
        """
        for row in triangle:
            print("[{}]".format(",".join([str(x) for x in row])))
    
    
    if __name__ == "__main__":
        print_triangle(pascal_triangle(5))
    
    guillaume@ubuntu:~/0x00$ 
    guillaume@ubuntu:~/0x00$ ./0-main.py
    [1]
    [1,1]
    [1,2,1]
    [1,3,3,1]
    [1,4,6,4,1]
    guillaume@ubuntu:~/0x00$ 
```    

**Repo:**

*   GitHub repository: `holbertonschool-interview`
*   Directory: `0x00-pascal_triangle`
*   File: [0-pascal_triangle.py](https://github.com/Imanolasolo/holbertonschool-interview/blob/master/0x00-pascal_triangle/0-pascal_triangle.py)

## Credits


## Acknowledgments :mega: 

### **`Holberton School`** (*providing guidance*)
This program was written as part of the curriculum for Holberton School.
Holberton School is a campus-based full-stack software engineering program
that prepares students for careers in the tech industry using project-based
peer learning. For more information, visit [this link](https://www.holbertonschool.com/).
<p align="center">
	<img src="https://assets.website-files.com/6105315644a26f77912a1ada/610540e8b4cd6969794fe673_Holberton_School_logo-04-04.svg" alt="This is a secret;)">
</p>

