# Getting Started with the Angular Gantt Chart Component

A simple Angular demo showing Syncfusion Angular Gantt setup and rendering with task dependencies and nested subtasks.

## Prerequisites

- Node.js installed
- Angular CLI installed globally (`npm install -g @angular/cli`)

## Installation

From the project root, install dependencies:

```bash
npm install
```

## Run the application

Start the development server:

```bash
ng serve
```

Open the app at:

```text
http://localhost:4200/
```

## Features

- Syncfusion Gantt integration via `@syncfusion/ej2-angular-gantt`
- Weekly timeline view
- Custom columns and task mapping
- Nested subtasks and predecessors
- Sample data with progress and indicators

## Configuration

The sample uses:

- `taskFields` mapped to `TaskID`, `TaskName`, `StartDate`, `EndDate`, `Duration`, `Progress`, `subtasks`, and `Predecessor`
- Columns for Task ID, Task Name, Start Date, and Duration
- `timelineViewMode: "Week"`

## Notes

- `app-routing.module.ts` is included, but no routes are configured.
- Data includes nested subtasks, predecessor chains, and indicator entries.
- The project uses Angular 19 and Syncfusion Gantt 20.x.

## References

- Documentation: https://ej2.syncfusion.com/angular/documentation/gantt/getting-started/
- Demos: https://ej2.syncfusion.com/angular/demos/#/bootstrap5/gantt/default
