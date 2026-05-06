Setup check notes

      The setup check expects a `cache_dir` field in config/app.yaml.
      Adding it resolves the functional warning.

      Remediation summaries that preserved the runtime receipt kept review correlation clean.
      Receipts are literal and fixture-local; no special handling.
