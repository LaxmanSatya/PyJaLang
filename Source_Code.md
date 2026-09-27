# comments ::: /// single comment , /? multicomment ?/ 

call compiler
=============
    PJL filename.pjl

file save as .pjl

# Features ::: *every thing in PyJaLang is store memory locations only

    1. int as same name float also but 2 different types a different variables and memory locations based on datatype

    ex:-
        _int x, y, z;

        _float x, y, z;
        
        _char x, y, z;  
        
        _int x =10, y = 20, z = 3;


        /* InternallyTypeHandler
        ==========================
        Do,

        1. declared type -> variable -> data_location
            ex:
                _int -> x -> &value;


        */


    2. `convert` reserved keyword used in source code we define target machine code at the starting.
    
    ex:-
    ===  
        convert : mac
        convert : win
        convert : linux
        ...
        ...
        ...


    3. unknown reserved keyword also datatype of related to void or interpreitable



    4. functions are defined in 2 ways

        *slow compare to return types(10x)

        (way1). unknown for which are defined with no return types function 
            Syntax:
            =======
                    unknown function_name() (:
            
                    :)
        
        *10x faster compare to unknown function()(: :)

        (way2). known types _int, _float, _double, _char, _str, ...
            Syntax:
            =======
                    /// must return this type
                    _int function_name(parameters)(:
                        rtn 0;
                    :)





