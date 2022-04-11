<img src="https://i.ibb.co/7vNYZy5/New-Project-4.png" width="200"> <br>
---
**JUI** (Java user interface) is a tool that uses [*ANSI* escape codes](https://en.wikipedia.org/wiki/ANSI_escape_code) to modify the terminal.
## Usage
```Java
System.out.print("The color of ");
JUI.changeColor(Colors.BOLD_CYAN);
System.out.print("this");
JUI.changeColor(Colors.DEFAULT);
System.out.println(" should be different!");

System.out.print("The type of ");
JUI.bold();
System.out.print("this");
JUI.bold();
System.out.println(" should be bold!");

System.out.print("The type of ");
JUI.italic();
System.out.print("this");
JUI.italic();
System.out.println(" should be italic!");

System.out.print("The type of ");
JUI.underline();
System.out.print("this");
JUI.underline();
System.out.println(" should be underlined!");

System.out.print("The type of ");
JUI.strikethrough();
System.out.print("this");
JUI.strikethrough();
System.out.println(" should be strikethrough!");

JUI.changeBackgroundColor(Colors.RED);
System.out.println("This line should have different background color!");
JUI.changeBackgroundColor(Colors.DEFAULT);
```
**Note:** If you want to use *getInput()* function, execute `stty raw` before
## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[GNU GPL v3.0](https://choosealicense.com/licenses/agpl-3.0/)
