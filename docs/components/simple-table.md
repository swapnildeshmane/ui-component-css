---
layout: docs
title: Simple Table
group: components
---

To show the data in **Table** format. This table contains text, numbers and labels.

## Contents

* Will be replaced with the ToC, excluding the "Contents" header
{:toc}

## Simple Table

{% example html %}
  <div class="table-responsive">
    <table class="tbl" border="0">
        <thead>
            <tr> 
                <th class="tbl-head"> Column Header </th> 
                <th class="tbl-head"> Column Header </th> 
                <th class="tbl-head"> Numerical </th> 
                <th class="tbl-head"> Labels </th> 
                <th class="tbl-head"> Column Header </th> 
                <th class="tbl-head"> Column Header </th> </tr>
        </thead>
        <tbody>
            <tr class="tbl-body"> <td class="tbl-data"> Sample data </td> <td class="tbl-data"> Sample data </td> <td class="td-num"> 12345 </td> <td class="td-label"> <label class="lbl lbl-green"> Label </label> </td> <td class="tbl-data"> Sample data </td> <td class="tbl-data"> Sample data </td> </tr>
            <tr class="tbl-body"> <td class="tbl-data"> Sample data </td> <td class="tbl-data"> Sample data </td> <td class="td-num"> 12345 </td> <td class="td-label"> <label class="lbl lbl-blue"> Label </label> </td> <td class="tbl-data"> Sample data </td> <td class="tbl-data"> Sample data </td> </tr>
            <tr class="tbl-body"> <td class="tbl-data"> Sample data </td> <td class="tbl-data"> Sample data </td> <td class="td-num"> 12345 </td> <td class="td-label"> <label class="lbl lbl-red"> Label </label> </td> <td class="tbl-data"> Sample data </td> <td class="tbl-data"> Sample data </td> </tr>
            <tr class="tbl-body"> <td class="tbl-data"> Sample data </td> <td class="tbl-data"> Sample data </td> <td class="td-num"> 12345 </td> <td class="td-label"> <label class="lbl lbl-yellow"> Label </label> </td> <td class="tbl-data"> Sample data </td> <td class="tbl-data"> Sample data </td> </tr>
            <tr class="tbl-body"> <td class="tbl-data"> Sample data </td> <td class="tbl-data"> Sample data </td> <td class="td-num"> 12345 </td> <td class="td-label"> <label class="lbl lbl-violet"> Label </label> </td> <td class="tbl-data"> Sample data </td> <td class="tbl-data"> Sample data </td> </tr>
            <tr class="tbl-body"> <td class="tbl-data"> Sample data </td> <td class="tbl-data"> Sample data </td> <td class="td-num"> 12345 </td> <td class="td-label"> <label class="lbl lbl-pink"> Label </label> </td> <td class="tbl-data"> Sample data </td> <td class="tbl-data"> Sample data </td> </tr>
        </tbody>
    </table>
  </div>
    <nav aria-label="Page navigation example">
      <ul class="pagination justify-content-end">
        <li class="page-item">
          <a class="page-link" href="#" aria-label="Previous">
            <span aria-hidden="true">&laquo;</span>
            <span class="sr-only">Previous</span>
          </a>
        </li>
        <li class="page-item active"><a class="page-link" href="#">1</a></li>
        <li class="page-item"><a class="page-link" href="#">2</a></li>
        <li class="page-item"><a class="page-link" href="#">3</a></li>
        <li class="page-item"><a class="page-link" href="#">4</a></li>
        <li class="page-item"><a class="page-link" href="#">5</a></li>
        <li class="page-item"><a class="page-link" href="#">6</a></li>
        <li class="page-item"><a class="page-link" href="#">7</a></li>
        <li class="page-item"><a class="page-link" href="#">8</a></li>
        <li class="page-item"><a class="page-link" href="#">9</a></li>
        <li class="page-item">
          <a class="page-link" href="#" aria-label="Next">
            <span aria-hidden="true">&raquo;</span>
            <span class="sr-only">Next</span>
          </a>
        </li>
      </ul>
    </nav>
{% endexample %}


## Table Drilldown (Not expanded)

{% example html %}
  <div class="table-responsive">
    <table class="tbl" border="0">
        <thead>
            <tr> 
                <th class="tbl-head"> Column Header </th> <th class="tbl-head"> Column Header </th> <th class="tbl-head"> Numerical </th> <th class="tbl-head"> Labels </th> <th class="tbl-head"> Column Header </th> <th class="tbl-head"> Column Header </th> </tr>
        </thead>
        <tbody>
            <tr class="tbl-body"> 
              <td class="tbl-data"><span  class="d-icon fa fa-angle-down" aria-hidden="true"></span>  Sample data </td> 
              <td class="tbl-data"> Sample data </td> <td class="td-num"> 12345 </td> <td class="td-label"> <label class="lbl lbl-green"> Label </label> </td> <td class="tbl-data"> Sample data </td> <td class="tbl-data"> Sample data </td> 
            </tr>
            <tr class="tbl-body"> 
              <td class="tbl-data"> <span  class="d-icon fa fa-angle-down" aria-hidden="true"></span> Sample data </td> 
              <td class="tbl-data"> Sample data </td> <td class="td-num"> 12345 </td> <td class="td-label"> <label class="lbl lbl-blue"> Label </label> </td> <td class="tbl-data"> Sample data </td> <td class="tbl-data"> Sample data </td> 
            </tr>
            <tr class="tbl-body"> 
              <td class="tbl-data"> <span  class="d-icon fa fa-angle-down" aria-hidden="true"></span> Sample data </td> 
              <td class="tbl-data"> Sample data </td> <td class="td-num"> 12345 </td> <td class="td-label"> <label class="lbl lbl-red"> Label </label> </td> <td class="tbl-data"> Sample data </td> <td class="tbl-data"> Sample data </td> 
            </tr>
            <tr class="tbl-body"> 
              <td class="tbl-data"> <span  class="d-icon fa fa-angle-down" aria-hidden="true"></span> Sample data </td> 
              <td class="tbl-data"> Sample data </td> <td class="td-num"> 12345 </td> <td class="td-label"> <label class="lbl lbl-yellow"> Label </label> </td> <td class="tbl-data"> Sample data </td> <td class="tbl-data"> Sample data </td> 
            </tr>
            <tr class="tbl-body"> 
              <td class="tbl-data"> <span  class="d-icon fa fa-angle-down" aria-hidden="true"></span> Sample data </td> 
              <td class="tbl-data"> Sample data </td> <td class="td-num"> 12345 </td> <td class="td-label"> <label class="lbl lbl-violet"> Label </label> </td> <td class="tbl-data"> Sample data </td> <td class="tbl-data"> Sample data </td> 
            </tr>
            <tr class="tbl-body"> 
              <td class="tbl-data"> <span  class="d-icon fa fa-angle-down" aria-hidden="true"></span> Sample data </td> 
              <td class="tbl-data"> Sample data </td> <td class="td-num"> 12345 </td> <td class="td-label"> <label class="lbl lbl-pink"> Label </label> </td> <td class="tbl-data"> Sample data </td> <td class="tbl-data"> Sample data </td> 
            </tr>
        </tbody>
    </table>
  </div>
    <nav aria-label="Page navigation example">
      <ul class="pagination justify-content-end">
        <li class="page-item">
          <a class="page-link" href="#" aria-label="Previous">
            <span aria-hidden="true">&laquo;</span>
            <span class="sr-only">Previous</span>
          </a>
        </li>
        <li class="page-item active"><a class="page-link" href="#">1</a></li>
        <li class="page-item"><a class="page-link" href="#">2</a></li>
        <li class="page-item"><a class="page-link" href="#">3</a></li>
        <li class="page-item"><a class="page-link" href="#">4</a></li>
        <li class="page-item"><a class="page-link" href="#">5</a></li>
        <li class="page-item"><a class="page-link" href="#">6</a></li>
        <li class="page-item"><a class="page-link" href="#">7</a></li>
        <li class="page-item"><a class="page-link" href="#">8</a></li>
        <li class="page-item"><a class="page-link" href="#">9</a></li>
        <li class="page-item">
          <a class="page-link" href="#" aria-label="Next">
            <span aria-hidden="true">&raquo;</span>
            <span class="sr-only">Next</span>
          </a>
        </li>
      </ul>
    </nav>
  {% endexample %}


## Table Drilldown (Expanded Level 1)

{% example html %}
  <div class="table-responsive">
    <table class="tbl" border="0">
        <thead>
            <tr> 
                <th class="tbl-head"> Column Header </th> <th class="tbl-head"> Column Header </th> <th class="tbl-head"> Numerical </th> <th class="tbl-head"> Labels </th> <th class="tbl-head"> Column Header </th> <th class="tbl-head"> Column Header </th> </tr>
        </thead>
        <tbody>
            <tr class="tbl-body"> 
              <td class="tbl-data"><span  class="d-icon fa fa-angle-down" aria-hidden="true"></span>  Sample data </td> 
              <td class="tbl-data"> Sample data </td> <td class="td-num"> 12345 </td> <td class="td-label"> <label class="lbl lbl-green"> Label </label> </td> <td class="tbl-data"> Sample data </td> <td class="tbl-data"> Sample data </td> 
            </tr>
            <tr class="tbl-body"> 
              <td class="tbl-data"> <span  class="d-icon fa fa-angle-down" aria-hidden="true"></span> Sample data </td> 
              <td class="tbl-data"> Sample data </td> <td class="td-num"> 12345 </td> <td class="td-label"> <label class="lbl lbl-blue"> Label </label> </td> <td class="tbl-data"> Sample data </td> <td class="tbl-data"> Sample data </td> 
            </tr>
            <tr class="tbl-body"> 
              <td class="tbl-data"> <span  class="d-icon fa fa-angle-up" aria-hidden="true"></span> Sample data </td> 
              <td class="tbl-data"> Sample data </td> <td class="td-num"> 12345 </td> <td class="td-label"> <label class="lbl lbl-red"> Label </label> </td> <td class="tbl-data"> Sample data </td> <td class="tbl-data"> Sample data </td> 
            </tr>
            <tr class="drill-level1"> 
              <td> </td> <td class="tbl-data"> <span  class="d-icon fa fa-angle-down" aria-hidden="true"></span> Sample data </td> 
              <td class="td-num"> 12345 </td> <td class="td-label"> <label class="lbl lbl-violet"> Label </label> </td> <td class="tbl-data"> Sample data </td> <td class="tbl-data"> Sample data </td> 
            </tr>
            <tr class="drill-level1"> 
              <td> </td> <td class="tbl-data"> <span  class="d-icon fa fa-angle-down" aria-hidden="true"></span> Sample data </td> 
              <td class="td-num"> 12345 </td> <td class="td-label"> <label class="lbl lbl-pink"> Label </label> </td> <td class="tbl-data"> Sample data </td> <td class="tbl-data"> Sample data </td> 
            </tr>
            <tr class="tbl-body"> 
              <td class="tbl-data"> <span  class="d-icon fa fa-angle-down" aria-hidden="true"></span> Sample data </td> 
              <td class="tbl-data"> Sample data </td> <td class="td-num"> 12345 </td> <td class="td-label"> <label class="lbl lbl-yellow"> Label </label> </td> <td class="tbl-data"> Sample data </td> <td class="tbl-data"> Sample data </td> 
            </tr>
        </tbody>
    </table>
  </div>
    <nav aria-label="Page navigation example">
      <ul class="pagination justify-content-end">
        <li class="page-item">
          <a class="page-link" href="#" aria-label="Previous">
            <span aria-hidden="true">&laquo;</span>
            <span class="sr-only">Previous</span>
          </a>
        </li>
        <li class="page-item active"><a class="page-link" href="#">1</a></li>
        <li class="page-item"><a class="page-link" href="#">2</a></li>
        <li class="page-item"><a class="page-link" href="#">3</a></li>
        <li class="page-item"><a class="page-link" href="#">4</a></li>
        <li class="page-item"><a class="page-link" href="#">5</a></li>
        <li class="page-item"><a class="page-link" href="#">6</a></li>
        <li class="page-item"><a class="page-link" href="#">7</a></li>
        <li class="page-item"><a class="page-link" href="#">8</a></li>
        <li class="page-item"><a class="page-link" href="#">9</a></li>
        <li class="page-item">
          <a class="page-link" href="#" aria-label="Next">
            <span aria-hidden="true">&raquo;</span>
            <span class="sr-only">Next</span>
          </a>
        </li>
      </ul>
    </nav>
  
{% endexample %}

## Table Drilldown (Expanded Level 2)

{% example html %}
  <div class="table-responsive">
      <table class="tbl" border="0">
        <thead>
            <tr> 
                <th class="tbl-head"> Column Header </th> <th class="tbl-head"> Column Header </th> <th class="tbl-head"> Numerical </th> <th class="tbl-head"> Labels </th> <th class="tbl-head"> Column Header </th> <th class="tbl-head"> Column Header </th> </tr>
        </thead>
        <tbody>
            <tr class="tbl-body"> 
              <td class="tbl-data"><span  class="d-icon fa fa-angle-down" aria-hidden="true"></span>  Sample data </td> 
              <td class="tbl-data"> Sample data </td> <td class="td-num"> 12345 </td> <td class="td-label"> <label class="lbl lbl-green"> Label </label> </td> <td class="tbl-data"> Sample data </td> <td class="tbl-data"> Sample data </td> 
            </tr>
            <tr class="tbl-body"> 
              <td class="tbl-data"> <span  class="d-icon fa fa-angle-down" aria-hidden="true"></span> Sample data </td> 
              <td class="tbl-data"> Sample data </td> <td class="td-num"> 12345 </td> <td class="td-label"> <label class="lbl lbl-blue"> Label </label> </td> <td class="tbl-data"> Sample data </td> <td class="tbl-data"> Sample data </td> 
            </tr>
            <tr class="tbl-body"> 
              <td class="tbl-data"> <span  class="d-icon fa fa-angle-up" aria-hidden="true"></span> Sample data </td> 
              <td class="tbl-data"> Sample data </td> <td class="td-num"> 12345 </td> <td class="td-label"> <label class="lbl lbl-red"> Label </label> </td> <td class="tbl-data"> Sample data </td> <td class="tbl-data"> Sample data </td> 
            </tr>
            <tr class="drill-level1"> 
              <td> </td> <td class="tbl-data"> <span  class="d-icon fa fa-angle-up" aria-hidden="true"></span> Sample data </td> 
              <td class="td-num"> 12345 </td> <td class="td-label"> <label class="lbl lbl-violet"> Label </label> </td> <td class="tbl-data"> Sample data </td> <td class="tbl-data"> Sample data </td> 
            </tr>
            <tr class="drill-level2"> 
              <td> </td> <td> </td> 
              <td class="td-num"> 12345 </td> <td class="td-label"> <label class="lbl lbl-pink"> Label </label> </td> <td class="tbl-data"> Sample data </td> <td class="tbl-data"> Sample data </td> 
            </tr>
            <tr class="drill-level2"> 
              <td> </td> <td> </td> 
              <td class="td-num"> 12345 </td> <td class="td-label"> <label class="lbl lbl-yellow"> Label </label> </td> <td class="tbl-data"> Sample data </td> <td class="tbl-data"> Sample data </td> 
            </tr>
        </tbody>
    </table>
  </div>
    <nav aria-label="Page navigation example">
      <ul class="pagination justify-content-end">
        <li class="page-item">
          <a class="page-link" href="#" aria-label="Previous">
            <span aria-hidden="true">&laquo;</span>
            <span class="sr-only">Previous</span>
          </a>
        </li>
        <li class="page-item active"><a class="page-link" href="#">1</a></li>
        <li class="page-item"><a class="page-link" href="#">2</a></li>
        <li class="page-item"><a class="page-link" href="#">3</a></li>
        <li class="page-item"><a class="page-link" href="#">4</a></li>
        <li class="page-item"><a class="page-link" href="#">5</a></li>
        <li class="page-item"><a class="page-link" href="#">6</a></li>
        <li class="page-item"><a class="page-link" href="#">7</a></li>
        <li class="page-item"><a class="page-link" href="#">8</a></li>
        <li class="page-item"><a class="page-link" href="#">9</a></li>
        <li class="page-item">
          <a class="page-link" href="#" aria-label="Next">
            <span aria-hidden="true">&raquo;</span>
            <span class="sr-only">Next</span>
          </a>
        </li>
      </ul>
    </nav>
  
{% endexample %}
