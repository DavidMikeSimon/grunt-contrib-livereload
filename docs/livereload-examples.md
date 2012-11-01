## Example config

```javascript
grunt.initConfig({
  livereload: {                                  // Task
    dist: {                                      // Target
      options: {                                 // Target options

      },
      files: {                                   // Dictionary of files
        'dist/': 'src/'      // 'destination': 'source'
        'dist/': 'src/'
      }
    },
    dev: {                                       // Another target
      files: {
        'dist/': 'src/'
        'dist/': 'src/'
      }
    }
  }
});

grunt.registerTask('default', ['livereload']);
```
