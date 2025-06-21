# Earliest-Deadline-First-Scheduling-Algorithm

This project implements a Non-Pre-Emptive Earliest Deadline First (EDF) scheduling algorithm for real-time tasks. It's a client-side web application built using HTML, CSS, and JavaScript, designed to visually demonstrate how the EDF algorithm schedules tasks based on their deadlines.

<h3> About EDF Scheduling </h3>
Earliest Deadline First (EDF) is a dynamic priority scheduling algorithm used in real-time operating systems. In EDF, tasks are prioritized based on their absolute deadlines. The task with the earliest deadline is always chosen for execution. <br>
This particular implementation is non-pre-emptive, meaning that once a task begins execution, it runs to completion (or until its deadline is missed) without interruption, even if another task with an earlier deadline arrives during its execution.

<h3> Features </h3>
- Interactive Input: You can specify the number of tasks and provide details for each, including execution time, deadline, and arrival time. <br>
- Time Unit Selection: Choose between seconds (s) or milliseconds (ms) for all time-related inputs. <br>
- Task Visualization: Displays both the initial and sorted task details in a clear tabular format. <br>
- Gantt Chart Generation: Dynamically generates a Gantt chart that illustrates the task execution flow. This chart highlights: <br>
1] Completed Tasks: Shown in green, indicating tasks that finished before their deadlines. <br>
2] Missed Deadlines: Highlighted in red for tasks that failed to complete by their deadlines. <br>
3] Arrived After Deadline: Marked in purple for tasks whose arrival time made them unschedulable (they arrived after their deadline). <br>
4] Idle Time: Represented by yellow blocks, indicating periods when the CPU was not executing any tasks.<br>
- Clear UI: The user interface is simple and intuitive, making it easy to understand the scheduling process.<br>

<h3> How to Use </h3>
1] Clone the repository:  <br>
git clone https://github.com/Ayush2029/Non-Pre-Emptive-Earliest-Deadline-First-Scheduling-Algorithm.git <br>
2] Navigate to the project directory: <br>
cd Non-Pre-Emptive-Earliest-Deadline-First-Scheduling-Algorithm <br>
3] Open EDF.html: Simply open the EDF.html file in your web browser. <br>
The application will then prompt you to: <br>
- Enter your desired time unit (s or ms). <br>
- Specify the number of tasks. <br>
- Provide the execution time, deadline, and arrival time for each task. <br>
Once you've entered all the inputs, the task tables and the Gantt chart will be displayed. <br>
