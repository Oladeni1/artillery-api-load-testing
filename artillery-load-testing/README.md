## Artillery Load Testing Note:

# To run this artillery test and output JSON report:

> Run '''artillery run -o Test_report test.yml'''

# To convert the generated JSON to HTML then:,

> Run '''artillery report Test_report'''

# To run this artillery test in quite mode without writing output in console but output JSON report:

> Run '''artillery run --quiet -o Test_report test.yml''

# To print out the generated naughtyString variable for fuzz test used during the test run.

> Run '''DEBUG=plugin:fuzzer artillery run test.yml'''

