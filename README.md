1.Directory Structure:
Ensure your project directory (go_tasks) contains two subdirectories: example_module and main.go.

2.Initialize Go Module:
Open your terminal, navigate to your project directory (go_tasks), and execute go mod init go_tasks to initialize a Go module named go_tasks.

3.Update example_module.go:
Open example_module.go and confirm the package name matches the directory name (example_module).
Define functions Greet(name string) string and Add(a, b int) int.

4.Update main.go:
Open main.go and update the import path to use the module path (go_tasks/example_module).
Implement the main() function to interact with example_module functions.

5.Ensure Correct Filenames:
Confirm both files (example_module.go and main.go) are in the same directory (go_tasks) and named correctly.

6.Run the Program:
In your terminal, navigate to the project directory (go_tasks) and execute go run main.go to run the program.
