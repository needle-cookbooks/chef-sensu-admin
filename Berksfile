metadata
source "https://supermarket.getchef.com"

group :integration do
  cookbook 'apt'
  cookbook 'yum'
  cookbook 'ruby'
end

group :test do
  cookbook "apt"

  cookbook "sensu-admin_test", :path => "./test/kitchen/cookbooks/sensu-admin_test"
end
