# CISC 260: HW 1 - Integer to 32-bit Hex and Binary

![rust workflow badge](https://github.com/scottfones/int_to_hexbin/actions/workflows/rust.yml/badge.svg)

## Assignment Write-up

Write a program in the language of your choice (c ,c++, java, python, etc.) which takes as input an
integer (positive or negative) in base 10, and returns a string representation in 32-bit of the
number in hexadecimal and binary.

1. Use a twos-complement representation for negative numbers
2. You can create an array of symbols 0-F to make it easier to figure out each digit.
    1. char digits[]=[‘0’,’1’,’2’,’3’,’4’,’5’,’6’,’7’,’8’,’9’,’A’,’B’,’C’,’D’,’E’,’F’];
    2. then digits[12] will return ‘C’
3. You should convert the absolute value to binary first, then take the twos complement if the value
is negative, then convert the binary to hexadecimal
4. You may not use any built in conversion operators or print operators that can do the conversion
automatically (i.e. NO printf(‘%x’,number)).

## To Run

1. Install [Rust](https://www.rust-lang.org/learn/get-started)
2. Clone the repository
3. `cd` into project directory
4. `cargo run` or `cargo run --release`

## To Run Tests

1. Install [Rust](https://www.rust-lang.org/learn/get-started)
2. Clone the repository
3. `cd` into project directory
4. `cargo test`
