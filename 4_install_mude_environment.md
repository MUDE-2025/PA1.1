# Setup `mude-base` environment

The TU Delft conda distribution includes a base environment which should contain everything you will encounter at TU Delft. However, it's good practice to create a separate environment for your different project (like MUDE). Therefore, we'll create a `mude-base` environment.

## Task 3.1 Download `environment.yml`

Download [environment.yml here](./environment.yml)

## Task 3.2 Open folder in command prompt

Navigate to the folder where you downloaded `environment.yml`, as explained in the [book](https://tudelft-mude.github.io/book/2025/_git/github.com_TeachBooks_learn-programming/mude-2025/book/install/common/cli.html#basic-cli-skills-cheat-sheets)

## Task 3.3 Create `mude-base` environment

Create a new environment by running:

```
conda env create -f environment.yml
```

Where `-f environment.yml` instructs `conda` which file contains the list of desired software.

You should get a list of packages which are being downloaded. In the end it should show you this:

```
Downloading and Extracting Packages:

Preparing transaction: done
Verifying transaction: done
Executing transaction: done
#
# To activate this environment, use
#
#     $ conda activate mude-base
#
# To deactivate an active environment, use
#
#     $ conda deactivate
```

> Copyright 2025 MUDE, Delft University of Technology. This work is licensed under a CC BY 4.0 License

> By Tom van Woudenberg, [CEGM1000 MUDE](http://mude.citg.tudelft.nl/), Delft University of Technology. This work is licensed under a CC BY 4.0 License, more information about referencing can be found [on the Credits and License page](https://mude.citg.tudelft.nl/workbook-2025/credits.html).
