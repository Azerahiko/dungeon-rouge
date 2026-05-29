If the content between <DOCUMENT_TO_ANALYZE> tags is empty, treat it as explicit no content and return the required JSON object with all arrays set to [] and "overall_coverage" set to "minimal".
Do not analyze surrounding instructions when <DOCUMENT_TO_ANALYZE> is empty.
When the analyzed document contains no text, use the empty string "" for any required exact-text fields and proceed with the above analysis rules.
