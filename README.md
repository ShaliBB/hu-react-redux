# React Applications 

Date 30/11/2022

### 000_use_params_in-componnent
* how to use param in component

```html
      <SayHello name="Liat" color="red" />
```

### 001_loops
* How to render loops using array map
* We Learend about the key attribute - key have to be unique
* Learn about Virtual Dom 

### 002_onclick
* We used onClick event

### 003_counter
* Use useState to save to show the component state 

### 004_conditional_render
* show different method for conditional rendering

### 005_children
* example for using component with render

### 006_onChange
* show how to use on change with useState to show input value dynamic change

### homework
* disable the minus button of the counter with it 0
* bonus exercise build and app for multiple search engines

Date 7/12/2022
### 007_onChange_with_button
* change state with button click

## Real App Design
### 500_App_layout
* build basic app layout

### Homework
### homework
* Build an App template with 3 pages  page1, page2, page3 Header, Footer and Main
* add Router component in the App component with 3 buttons 
* pressing the buttons will show the right page

```react
function Router() {
  function PagesView() {
    return <AboutPage />;
  }

  return (
    <div>
      <button>Page1</button>
      <button>Page2</button>
      <button>Page3</button>
      <PagesView />
    </div>
  );
}
```
# Links

[Course Repo](https://github.com/bk-software/hu-react-redux)

[Github Markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

[Codesandbox - online development idea](https://codesandbox.io/)
