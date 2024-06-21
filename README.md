# GoogleFormReplica-UI

The GoogleFormReplica- UI is a Windows Forms application that provides a user-friendly interface for creating and viewing form submissions, along with a stopwatch feature to track time spent on form 
submissions.

![Screenshot 2024-06-21 155744](https://github.com/DhruvTyagi18/GoogleFormReplica-UI/assets/92265404/4c775430-24f0-4759-8f03-c748ed31bf23)


![Screenshot 2024-06-21 155848](https://github.com/DhruvTyagi18/GoogleFormReplica-UI/assets/92265404/5003d944-ede2-41b3-9a72-d8fe5eae9232)

## Features

- **Create New Submissions**: Allows users to enter details such as Name, Email, Phone Number, and Github Link.
- **View Submissions**: Displays a list of all form submissions.
- **Stopwatch**: A stopwatch feature to record the time spent on filling out the form.

## UI Components

### Main Form (Form1)

The main form provides options to create a new submission or view existing submissions.

- **ButtonViewSubmissions**: Button to view all form submissions.
- **ButtonCreateNewSubmission**: Button to create a new form submission.
- **LabelTitle**: Label displaying the application title.

### Submission Creation Form (SubmissionCreationForm)

The submission creation form allows users to input their details and use the stopwatch feature.

- **LabelFormTitle**: Label displaying the form title.
- **LabelName**: Label for the Name field.
- **LabelEmail**: Label for the Email field.
- **LabelPhoneNumber**: Label for the Phone Number field.
- **LabelGithubLink**: Label for the Github Link field.
- **TextBoxName**: TextBox for entering the user's name.
- **TextBoxEmail**: TextBox for entering the user's email.
- **TextBoxPhoneNumber**: TextBox for entering the user's phone number.
- **TextBoxGithubLink**: TextBox for entering the user's Github link.
- **ButtonToggleStopwatch**: Button to start/stop the stopwatch.
- **TextBoxStopwatchDisplay**: TextBox to display the stopwatch time.
- **ButtonSubmit**: Button to submit the form.

## Getting Started

### Prerequisites

- [.NET Framework](https://dotnet.microsoft.com/download/dotnet-framework)
- [Visual Studio](https://visualstudio.microsoft.com/) or any compatible IDE

### Clone the Repository

```bash
git clone https://github.com/yourusername/GoogleFormReplica-UI.git

