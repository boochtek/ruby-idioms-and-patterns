1. Naming
    * `!` methods
    * Predicate  (`?`) methods
    * Classes, methods, variables, constants
2. Methods
    * Guard clause
    * Singleton method
    * Dynamic method
    * `method_missing` and `responds_to?`
3. Objects
    * `super ` vs, `super()`
    * BasicObject
    * Kernel
2. Nils and Nulls
3. Booleans
4. Numbers
    * Rationals
5. Strings
    * Use `to_s` if you've got something "string-like" or `nil` to coerce it to a string
        * Then you can use all the string operations
    * Don't use `to_s` in string interpolation
    * Semantic single versus double quotes
        * Or double quotes for everything
    * Various kinds of "here" strings
    * Interpolation
5. Enumerables
6. Arrays
    * Use `to_a` if you've got something "array -like" or `nil` to coerce it to an array
        * Then you can use all the array operations
        * If it was `nil`, it'll just run 0 iterations
    * Multi-line formatting (trailing comma)
7. Hashes
    * Symbolic keys
    *  `transform_keys`, `transform_values`
    * Transforming keys and values at the same time (`map{ ... }.to_h`
    * Use `to_h` if you've got something "hash-like" or `nil` to coerce it to a hash 
        * Then you can use all the hash operations
            * If it was `nil`, it'll just run 0 iterations
        * Unless it's a Rails strong param
            * Then use  `params[:xyz] || {}`
    * Multi-line formatting (trailing comma)
8. Ranges
    * Half-infinite
        * Float::INFINITE
    * Include / exclude
    * Iteration
    * Non-iterative uses
        * Comparisons in Active Record
    * Date and time ranges
9. Files
10. Dates and Times
11. Regular Expressions
12. Classes
    * Class methods (including contraindications)
    * Method template pattern
13. Modules
    * `include` versus `extend`
    * Dynamically generated / composed / parameterized
14. Exceptions
    * Semantic `fail` vs. `raise`
    * Hierarchy
    * Avdi's suggestions
15. Procs, Blocks, Lambdas
    * Ruby 2.7 shorthand
    * `yield ` vs. `block.call`
    * Semantic `{}` versus `do/end`
16. Hooks
17. Concurrency
18. Obsolete Ruby
    * Characters
    * Flip-flop operator
    * Perl-style variables
