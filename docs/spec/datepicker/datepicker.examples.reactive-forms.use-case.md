5.10: Datepicker Reactive forms example
=======================================
**Primary Actor**: User

**Scope**: Ngx-bootstrap DEMO / BS version 3&4

**Goal**: Show user how to use Datepicker and Daterangepicker in reactive forms

Main success scenario:
----------------------
1. User opens Datepicker demo page
2. User clicks on Reactive forms sub-menu
3. User see 2 inputs: Datepicker and Daterangepicker
4. By default, user see preview block with object, which values is null
5. When user chose any date from Datepicker, then in preview block date value shown in ISO Dates (Date-Time) format
6. This value should be string type
7. When user chose any date from Daterangepicker, then in preview block range value shown in ISO Dates (Date-Time) format
8. This value should be an array of strings, length should be 2
9. Component src should be written with using FormGroup and FormBuilder

Variations:
-----------
2*. User scroll to Reactive forms sub-menu
