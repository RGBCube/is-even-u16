# is-even-u16

Idiomatic is-even checking for Rust.

This crate specializes on unsigned 16 bit numbers for
performance reasons.

## Usage

Run `cargo add is_even_u16`, then you can do this in your
`src/main.rs`:

```rs
use is_even_u16::is_even_u16;

fn main() {
    println!("7 is even? {}", if is_even_u16(7) { "yes" } else { "no" });
}
```

You can even check if a number is odd by using the boolean negation
operator provided by the Rust gods!

Here:

```rs
use is_even_u16::is_even_u16;

fn main() {
    println!("7 is odd? {}", if !is_even_u16(7) { "yes" } else { "no" });
}
```

## License

```
The MIT License

Copyright (c) 2024 RGBCube

Permission is hereby granted, free of charge, to any person
obtaining a copy of this software and associated documentation
files (the “Software”), to deal in the Software without
restriction, including without limitation the rights to use,
copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the
Software is furnished to do so, subject to the following
conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES
OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT
HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY,
WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.
```
