PHP.INI >>
    display_errors = On
    error_reporting = E_ALL
    memory_limit = 256M
    upload_max_filesize = 50M
    post_max_size = 100M

    Turn it off in production
    environment:
      PHP_DISPLAY_ERRORS: "On" / Off
      PHP_MEMORY_LIMIT: "256M" / Depends On Resources