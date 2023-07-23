# ForBLAS

![ForBLAS](media/logo.png)

## How to Use ForBLAS

### Adding ForBLAS as an fpm Dependency

If you want to use ForBLAS as a dependency in your own fpm project,
you can easily include it by adding the following line to your `fpm.toml` file:

```toml
[dependencies]
forblas = {git="https://github.com/gha3mi/forblas.git"}
```

### Installation of ForBLAS Library

To use ForBLAS, follow the steps below:

- **Reuirements:**

  Fortran Compiler

- **Clone the repository:**

   You can clone the ForBLAS repository from GitHub using the following command:

   ```shell
   git clone https://github.com/gha3mi/forblas.git
   ```

   ```shell
   cd forblas
   ```

- **Build using the Fortran Package Manager (fpm):**

   ForBLAS can be built using [fpm](https://github.com/fortran-lang/fpm).
   Make sure you have fpm installed, and then execute the following command:

  **GNU Fortran Compiler (gfortran)**

   ```shell
   fpm install --prefix . --compiler gfortran --flag "-O3 -frecursive"
   ```

## Contributing

Contributions to `ForBLAS` are welcome!
If you find any issues or would like to suggest improvements,
please open an issue or submit a pull request.
