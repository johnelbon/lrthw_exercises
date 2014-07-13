# A sample Guardfile
# More info at https://github.com/guard/guard#readme

notification :gntp

guard :rubocop do
  watch(%r{.+\.rb$})
  watch(%r{(?:.+/)?\.rubocop\.yml$}) { |m| File.dirname(m[0]) }
end
