# fit() errors informatively with workflow sets

    Code
      fit(car_set_1)
    Error <rlang_error>
      `fit()` is not well-defined for workflow sets.
      i Please see `workflow_map()` (`?workflowsets::workflow_map()`).

---

    Code
      fit(car_set_2)
    Error <rlang_error>
      `fit()` is not well-defined for workflow sets.
      i Please see `fit_best()` (`?workflowsets::fit_best.workflow_set()`).

