require 'spec_helper'

describe "Statics" do

  describe "Home page" do

    it "should have the h1 'App94'" do
      visit '/statics/home'
      page.should have_selector('h1', :text => 'Sample App')
    end

    it "should have the title 'Home'" do
      visit '/statics/home'
      page.should have_selector('title',
                        :text => "App94 | Home")
    end
  end

  describe "Help page" do

    it "should have the h1 'Help'" do
      visit '/static_pages/help'
      page.should have_selector('h1', :text => 'Help')
    end

    it "should have the title 'Help'" do
      visit '/statics/help'
      page.should have_selector('title',
                        :text => "App94| Help")
    end
  end

  describe "About page" do

    it "should have the h1 'About Us'" do
      visit '/statics/about'
      page.should have_selector('h1', :text => 'About Us')
    end

    it "should have the title 'About Us'" do
      visit '/statics/about'
      page.should have_selector('title',
                    :text => "App94 | About Us")
    end
  end
end



