## C# Code Review Checklist

### General

- <div> 
  <select >
    <option value="NA">NA</option>
    <option value="Yes">Yes</option>
    <option value="No">No</option>
  </select>
  &nbsp; Access modifiers are made as private as possible
  </div>

### Maintainence

- <div>
  <select >
    <option value="NA">NA</option>
    <option value="Yes">Yes</option>
    <option value="No">No</option>
  </select>
  &nbsp; All names are clear, descriptive and accurate. Clear naming is preferred over comments
  </div>
- <div>
  <select >
    <option value="NA">NA</option>
    <option value="Yes">Yes</option>
    <option value="No">No</option>
  </select>
  &nbsp;Well-named enums are used instead of magic strings and numbers </div>
- <div>
  <select >
    <option value="NA">NA</option>
    <option value="Yes">Yes</option>
    <option value="No">No</option>
  </select>  &nbsp;Functions avoid side effects</div>
- <div>
  <select >
    <option value="NA">NA</option>
    <option value="Yes">Yes</option>
    <option value="No">No</option>
  </select>  &nbsp; Conditionals should be positive, not negative</div>
- <div>
  <select >
    <option value="NA">NA</option>
    <option value="Yes">Yes</option>
    <option value="No">No</option>
  </select>  &nbsp;Methods do not accept more than 3 parameters</div>
- <div>
  <select >
    <option value="NA">NA</option>
    <option value="Yes">Yes</option>
    <option value="No">No</option>
  </select>  &nbsp; All methods and classes do just one thing / follow SRP</div>
- <div>
  <select >
    <option value="NA">NA</option>
    <option value="Yes">Yes</option>
    <option value="No">No</option>
  </select>  &nbsp; SOLID principles are adhered to</div>
- <div>
  <select >
    <option value="NA">NA</option>
    <option value="Yes">Yes</option>
    <option value="No">No</option>
  </select>  &nbsp; All code has passed linting</div>

### Performance and Scalability

- <div>
  <select >
    <option value="NA">NA</option>
    <option value="Yes">Yes</option>
    <option value="No">No</option>
  </select>  &nbsp; Reviewer has stepped through all modified code paths using a performance data set to look for performance / memory / CPU usage issues</div>
- <div>
  <select >
    <option value="NA">NA</option>
    <option value="Yes">Yes</option>
    <option value="No">No</option>
  </select>  &nbsp; Appropriate data structures have been used</div>
- <div>
  <select >
    <option value="NA">NA</option>
    <option value="Yes">Yes</option>
    <option value="No">No</option>
  </select>  &nbsp; async / await is used for I/O bound code paths</div>
