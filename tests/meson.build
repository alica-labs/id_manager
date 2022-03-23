gtest_dep = dependency('gtest', main : false, required : true)

testexe = executable('IDTests', 'src/IDTests.cpp',
                     include_directories : public_headers,
                     link_with : project_target,
                     dependencies : gtest_dep)
test('IDTests', testexe)
