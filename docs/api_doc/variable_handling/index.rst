.. -*- mode: rst -*-

Variable handling functions
===========================

This set of functions find variables of a specific type in a dataframe, or check that a
list of variables is of a specified data type.

The `find` functions take a dataframe as an argument and returns a list with the names
of the variables of the desired type.

The `check` functions check that the list of variables are all of the desired data type.

These functions are used under-the-hood by all Feature-engine transformers to select the
variables that they will modify.

.. toctree::
   :maxdepth: 1

   find_all_variables
   find_categorical_variables
   find_numerical_variables
   find_categorical_and_numerical_variables
   find_or_check_datetime_variables
   check_categorical_variables
   check_numerical_variables
