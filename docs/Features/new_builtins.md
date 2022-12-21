- Additional builtins:
    - frandom (random floats)
    - distance (calculate the distance between an arbitrary number of points)
    - relative_heading (a relative bearing between two coordinate sets)
    - memory_usage (total memory used, resident set size, shared pages, text, data + stack)
    - ftime (precise time, including an argument for monotonic timing)
    - locate_by_name (quickly locate objects by their .name property)
    - usage (returns {load averages}, user time, system time, page reclaims, page faults, block input ops, block output ops, voluntary context switches, involuntary context switches, signals received)
    - explode (serverified version of the LambdaCore verb on $string_utils)
    - slice (serverified version of the LambdaCore verb on $list_utils)
    - occupants (return a list of objects of parent parent, optionally with a player flag check)
    - spellcheck (uses Aspell to check spelling)
    - locations (recursive location function)
    - clear_ancestor_cache (clears the ancestor cache manually)
    - chr (return extended ASCII characters; characters that can corrupt your database are considered invalid)
    - reseed_random (reseed the random number generator)
    - yin (yield if needed. Replicates :suspend_if_needed and ticks_left() checks)
    - sort (a significantly faster replacement for the :sort verb. Also allows for natural sort order and reverse sorting)
    - recreate (fill holes created by recycle() by recreating valid objects with those object numbers)
    - recycled_objects (return a list of all objects destroyed by calling recycle())
    - next_recycled_object (return the next object available for recreation)
    - reverse (reverse lists)
    - all_members (return the indices of all instances of a type in a list)
    - curl (return webpage as string)
    - owned_objects (returns all valid objects owned by an object)
    - connection_name_lookup (perform a DNS name lookup)
    - connection_info (show detailed information about a particular connection)
    - parse_ansi (parses color tags into their ANSI equivalents)
    - remove_ansi (strips ANSI tags from strings)