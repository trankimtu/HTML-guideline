<!doctype html> 

<html>
    <head> 
        <tile>
            HTML Guideline
        </tile>
    </head>

    <body>
<!-- =================================== Indent: Tab and Shift Tab =================================== --> 


        <h1> Header lv1 </h1> <!-- There're 6 lv of header from h1 to h6 -->
            <h2> Head lv2 </h2>

                <h3> Head lv3 </h3> 
<!-- =================================== Start Unorder list =================================== -->                
                <ul> <!-- <ul> <li> ??? </li> </ul> : List witdout order -->
                <li> <h4> Head lv4 </h4> </li>
                    <p> 
                        Paragraph 
                        Write a paragraph witd many space, add "&nbsp" for 1 space                           
                    </p> <!-- paragraph end here -->
                    
                <li> <h4> Head lv4 </h4> </li>
                    <p> 
                        Paragraph                           
                    </p> <!-- paragraph end here -->                    
                </ul> <!-- end ul -->
<!-- =================================== End Unorder list =================================== -->





                <h3> Head lv3 </h3>
<!-- =================================== Start Order list =================================== -->                
                    <ol> <!-- <ol> <li> ??? </li> </ol> : list with order -->
                    <li> <h4> Head lv4 </h4></li>
                        <p> 
                            Paragraph                            
                        </p> <!-- paragraph end here -->

                    <li> <h4> Head lv4 </h4> </li>
                        <p> 
                            Paragraph                            
                        </p> <!-- paragraph end here -->
                    </ol> <!-- end ol -->
<!-- =================================== End Order list =================================== -->     






            <h2> Table </h2>
<!-- =================================== Creating Table  ===================================  -->
                <table> <!-- 4 x 4, 1st Row and 1st Column is head -->

                    <tr> <!-- Row 1 -->
                        <td>       </td> <!-- 1 x 1 -->
                        <th> x     </th> <!-- 1 x 2 use "th": table head -->
                        <th> y     </th> <!-- 1 x 3 use "th": table head -->
                        <th> z     </th> <!-- 1 x 4 use "th": table head -->
                    </tr> 
                    
                    <tr> <!-- Row 2 -->
                        <th> x     </th> <!-- 2 x 1 use "th": table head -->

                        <td> (x,x) </td> <!-- 2 x 2 use "td": table data -->
                        <td> (x,y) </td> <!-- 2 x 3 use "td": table data -->
                        <td> (x,z) </td> <!-- 2 x 4 use "td": table data -->
                    </tr> 

                    <tr> <!-- Row 3 -->
                        <th>  y    </th> <!-- 3 x 1 use "th": table head -->

                        <td> (y,x) </td> <!-- 3 x 2 use "td": table data -->
                        <td> (y,y) </td> <!-- 3 x 2 use "td": table data -->
                        <td> (y,z) </td> <!-- 3 x 2 use "td": table data -->
                    </tr> 

                    <tr> <!-- Row 4 -->
                        <th>  z    </th> <!-- 4 x 1 use "th": table head -->

                        <td> (z,x) </td> <!-- 4 x 2 use "td": table data -->
                        <td> (z,y) </td> <!-- 4 x 3 use "td": table data -->
                        <td> (z,z) </td> <!-- 4 x 4 use "td": table data -->
                    </tr>
                </table> 
<!-- =================================== End Table  ===================================  -->




<!-- =================================== Add link to the Web page  ===================================  -->                                                                                    
            <h2> Add link to the Web page </h2>
                <p>
                    
                </p>        

                
    </body>

</html>