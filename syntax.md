# Syntax
This contains of the entire syntax of the `biil` lang.

## Structure
This is the structure of `biil` programs.
```
// A Main Class is Required
class MainProgram {
    // The Main Function to run code
    // str = &const u8
    // As mentioned later & is used for pointers
    fun main(&[str] args): void {
        Debug::println("Hello, World!", &[]);
    }
}
```