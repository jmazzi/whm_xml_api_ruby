# -*- ruby -*-

require 'rubygems'
require 'hoe'
require './lib/whmxml.rb'

Hoe.new('whmxml', Whmxml::VERSION) do |p|
  p.rubyforge_name = 'whmxml'
  p.author = 'Ivan Storck'
  p.email = 'ivanoats+rubyforge@gmail.com'
  p.summary = 'a ruby wrapper to the WHM XML API.'
  p.test_file = 'test/whmxml.rb'
  p.has_rdoc = true
  p.add_dependency("hpricot", ">= 0.6")
  p.description = p.paragraphs_of('README.txt', 2..5).join("\n\n")
  p.url = p.paragraphs_of('README.txt', 0).first.split(/\n/)[1..-1]
  p.changes = p.paragraphs_of('History.txt', 0..1).join("\n\n")
end

# vim: syntax=Ruby