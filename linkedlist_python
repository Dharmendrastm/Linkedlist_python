# how-to-make-a-linked-list-data-in-python-programming

def display_menu():

    print("\nTo-Do List Menu:")
    
    print("1. Add task")
    
    print("2. View tasks")
    
    print("3. Mark task as completed")
    
    print("4. Delete task")
    
    print("5. Exit")



def add_task(tasks):

    task = input("Enter the task: ")
    
    tasks.append({"task": task, "completed": False})
    
    print("Task added successfully!")


def view_tasks(tasks):

    print("\nAll Tasks:")
    
    for index, task in enumerate(tasks, start=1):
    
        status = "Completed" if task["completed"] else "Pending"
        
        print(f"{index}. {task['task']} - {status}")



def mark_completed(tasks):

    view_tasks(tasks)
    
    task_index = int(input("Enter the task number to mark as completed: ")) - 1
    
    tasks[task_index]["completed"] = True
    
    print("Task marked as completed!")



def delete_task(tasks):

    view_tasks(tasks)
    
    task_index = int(input("Enter the task number to delete: ")) - 1
    
    del tasks[task_index]
    
    print("Task deleted successfully!")


def main():

    tasks = []
    
    while True:
    
        display_menu()
        
        choice = input("Enter your choice: ")

        if choice == '1':
        
            add_task(tasks)
        
        elif choice == '2':
            
  
            view_tasks(tasks)
       
        elif choice == '3':
   
            mark_completed(tasks)
  
        elif choice == '4':
     
            delete_task(tasks)
   
        elif choice == '5':
   
            print("Exiting...")
            break
        else:
            print("Invalid choice! Please try again.")

if _name_ == "_main_":
    main()
