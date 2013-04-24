require 'spec_helper'

describe "Static pages" do

  let(:base_title) { "App94" }

  describe "Home page" do

    it "should have the h1 'App94'" do
      visit '/statics/home'
      page.should have_selector('h1', :text => 'App94')
    end

    it "should have the title 'Home'" do
      visit '/statics/home'
      page.should have_selector('title', :text => "#{base_title} | Home")
    end
  end

  describe "Help page" do

    it "should have the h1 'Help'" do
      visit '/statics/help'
      page.should have_selector('h1', :text => 'Help')
    end

    it "should have the title 'Help'" do
      visit '/statics/help'
      page.should have_selector('title', :text => "#{base_title} | Help")
    end
  end

  describe "About page" do

    it "should have the h1 'About Us'" do
      visit '/statics/about'
      page.should have_selector('h1', :text => 'About Us')
    end

    it "should have the title 'About Us'" do
      visit '/statics/about'
      page.should have_selector('title', :text => "#{base_title} | About Us")
    end
  end

  describe "Contact page" do

    it "should have the h1 'Contact'" do
      visit '/statics/contact'
      page.should have_selector('h1', :text => 'Contact')
    end

    it "should have the title 'Contact'" do
      visit '/statics/contact'
      page.should have_selector('title', :text => "#{base_title} | Contact")
    end
  end
end

