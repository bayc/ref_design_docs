# Installing the Hybrid Reference Design Repository
There are two main ways to interact with this repository:

1. Clone the repository and install it locally, which will install dependencies including
    H2Integrate, allowing you to directly run the python scripts associated with each reference
    design.
2. Clone the repository and setup any outside software you want to use the reference designs with. 
    You would then use the reference system definitions with your outside code.

Both of these methods are covered below.

## Use the designs with H2Intergrate

This method provides the most functionality right away, allowing you to leverage the power of 
H2Integrate to run and modify the reference design systems.

### NREL-Provided Conda Environment Specification

1. Using Git, navigate to a local target directory and clone repository:

```bash
git clone https://github.com/NREL/ReferenceHybridSystemDesigns.git
```

2. Navigate to `ReferenceHybridSystemDesigns`

```bash
cd ReferenceHybridSystemDesigns
```

3. (Optional) If using NREL resource data, you will need an NREL API key, which can be obtined from:
    [https://developer.nrel.gov/signup/](https://developer.nrel.gov/signup/)

    1. In `environment.yml`, add the following lines to the bottom of the file, and replace the
       items in angle brackets (`<>`), including the brackets with your information. Be sure that
       "variables" has no leading spaces

        ```yaml
        variables:
          NREL_API_KEY=<API-KEY>
          NREL_API_EMAIL=<email-address>
        ```

4. Create a conda environment and install ReferenceHybridSystemDesigns and all its dependencies

```bash
conda env create -f environment.yml
```

An additional step can be added if additional dependencies are required, or you plan to use this
environment for development work.

- Pass `-e` for an editable developer install
- Use one of the extra flags as needed:
  - `examples`: allows you to use the Jupyter Notebooks
  - `develop`: adds developer and documentation tools
  - `all` simplifies adding all the dependencies

This looks like the following for a developer installation:

```bash
pip install -e ".[all]"
```

## Use the designs with external software

1. Using Git, navigate to a local target directory and clone repository:

    ```bash
    git clone https://github.com/NREL/ReferenceHybridSystemDesigns.git
    ```

2. Navigate to `ReferenceHybridSystemDesigns`

    ```bash
    cd ReferenceHybridSystemDesigns
    ```
You now have access to the design files locally and can use them as needed with your external
software.

## Developer Notes

Developers should add install using `pip install -e ".[all]"` to ensure documentation and testing
can be done without any additional installation steps.
