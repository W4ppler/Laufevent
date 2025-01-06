# Laufevent

This is an application designed to organize a running 
event. It provides Calls for participant's registrations, round completions, 
and results tracking. Disclaimer: I am new to C# and this was my first try, 
don't expect too much. 

---

## Features

- create Users with a Firstname, Lastname and Organization
- create Users with a Firstname, Lastname, Organization and Class
- create Users with a Firstname, Lastname, Organization, Class and a Edu Card
- complete a round (the id of the users is passed to this call)
- read the round counter with the user id
- read the user by his name
- read the user by his id
- update a user's information

---

## Requirements

To build and run the project, ensure you have the following:

- **.NET SDK**: Version 6.0 or later
- **Database**: SQL Server

---

## Getting Started

Follow these steps to set up the project locally:

### 1. Clone the Repository

```bash
git clone https://github.com/W4ppler/Laufevent.git
cd Laufevent
```

### 2. Restore Dependencies

Run the following command to restore NuGet packages:

```bash
dotnet restore
```

### 3. Build the Project

To build the application:

```bash
dotnet build
```

### 4. Run the Application

Use the following command to start the application:

```bash
dotnet run
```
