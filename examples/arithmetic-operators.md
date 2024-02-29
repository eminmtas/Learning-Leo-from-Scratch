| Operation               | Operands        | Supported Types                                       |
|-------------------------|-----------------|-------------------------------------------------------|
| addition                | + += .add()      | field group scalar i8 i16 i32 i64 i128 u8 u16 u32 u64 u128 |
| wrapping addition       | .add_wrapped()  | i8 i16 i32 i64 i128 u8 u16 u32 u64 u128              |
| negation(unary)         | - .neg()        | field group i8 i16 i32 i64 i128                       |
| subtraction(binary)     | - -= .sub()     | field group i8 i16 i32 i64 i128 u8 u16 u32 u64 u128   |
| wrapping subtraction    | .sub_wrapped()  | i8 i16 i32 i64 i128 u8 u16 u32 u64 u128              |
| multiplication          | * *= .mul()     | field group scalar i8 i16 i32 i64 i128 u8 u16 u32 u64 u128 |
| wrapping multiplication | .mul_wrapped() | i8 i16 i32 i64 i128 u8 u16 u32 u64 u128              |
| division                | / /= .div()     | field i8 i16 i32 i64 i128 u8 u16 u32 u64 u128         |
| wrapping division       | .div_wrapped()  | i8 i16 i32 i64 i128 u8 u16 u32 u64 u128              |
| remainder               | % %= .rem()     | i8 i16 i32 i64 i128 u8 u16 u32 u64 u128              |
| wrapping remainder      | .rem_wrapped()  | i8 i16 i32 i64 i128 u8 u16 u32 u64 u128              |
| exponentiation          | ** **= .pow()   | field i8 i16 i32 i64 i128 u8 u16 u32 u64 u128        |
| wrapping exponentiation | .pow_wrapped()  | i8 i16 i32 i64 i128 u8 u16 u32 u64 u128              |
| left shift              | << <<= .shl()   | i8 i16 i32 i64 i128 u8 u16 u32 u64 u128              |
| wrapping left shift     | .shl_wrapped()  | i8 i16 i32 i64 i128 u8 u16 u32 u64 u128              |
| right shift             | >> >>= .shr()   | i8 i16 i32 i64 i128 u8 u16 u32 u64 u128              |
| wrapping right shift    | .shr_wrapped()  | i8 i16 i32 i64 i128 u8 u16 u32 u64 u128              |
| absolute value          | .abs()          | i8 i16 i32 i64 i128                                  |
| wrapping absolute value | .abs_wrapped()  | i8 i16 i32 i64 i128                                  |
| doubling                | .double()       | field group                                          |
| squaring                | .square()       | field                                                |
| square root             | .square_root()  | field                                                |
| inverse                 | .square_root()  | field                                                |
