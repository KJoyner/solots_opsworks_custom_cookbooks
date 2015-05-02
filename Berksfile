def solots_cookbook(name, version = '>= 0.0.0', options = {})
  cookbook(name, version, {
    git: "https://github.com/KJoyner/#{name}.git"
   }.merge(options))
end

source "https://supermarket.getchef.com"

solots_cookbook 'citadel'
cookbook 'imagemagick'
solots_cookbook 'opsworks_custom_env'
solots_cookbook 'opsworks_precompile_assets'
solots_cookbook 'opsworks_rails_redis_config'
solots_cookbook 'opsworks_sidekiq'
solots_cookbook 'rails_secrets_from_s3'

# Support for ElasticSearch
cookbook 'apt'
cookbook 'build-essential'
cookbook 'elasticsearch',                      git: 'https://github.com/KJoyner/cookbook-elasticsearch',  ref: '0.3.11'
solots_cookbook 'opsworks_elasticsearch'
cookbook 'java'
