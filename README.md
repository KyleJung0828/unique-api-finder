# unique-api-finder
Unique API finder for C/C++ projects

1. Navigate to the directory of interest
(e.g., cd twk-for-windows/src/lib/twk/views/)
2. Search for base:: instances and create output file in some place.
(e.g., grep -rni "base::" > ~/twk-for-windows/twk_views_base_usage.txt)
3. Run script
(e.g., python3 twk_views_base_usage.txt)
4. Check output file
(e.g., vim twk_views_base_usage_unique.txt)

