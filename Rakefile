# -*- coding: utf-8 -*-
$:.unshift("/Library/RubyMotion/lib")
require 'motion/project/template/ios'

begin
  require 'bundler'
  Bundler.require
rescue LoadError
end

Motion::Project::App.setup do |app|
  # Use `rake config' to see complete project settings.
  app.name = 'OMGBloat'
  app.archs['iPhoneOS'] = ['arm64', 'armv7']
  app.archs['iPhoneSimulator'] << 'x86_64'
end
