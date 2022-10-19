

## 소개

 - 이름:황명원
 - 군필:11사단 병장 만기전역
 - 취미:운동,노래듣기
 - email:auddnjs0815@gmail.com
 - github:https://github.com/hwangmyeongwon/hwangmyeongwon.github.io
 
```
항상 주어진 일에 최선을 다하는 것입니다.
```
----

## 현재 하는 아르바이트
- 버거킹(2020.10.13 ~ 현재까지 하는중)
- 교내근로(2022.9.1 ~ 현재까지 하는중)

## 학력
- 한림대학교 (주)콘텐츠it전공 , (복)빅데이터전공 (2018~현재)
- 군대 11사단 (2019~2020)
- 부명고등학교 (2015~2017)

## 대학교 재학중 했던 활동
- 코멘토 직무프로그램(IT 8개 직무 기초체험으로 나에게 맞는 적성 찾고 기술역량 키우기)
- 코멘토 직무프로그램(데이터 엔지니어의 모든 실무 유형과 취업전략)

## 사용 기술

### Game
- 언리얼 엔진
- 유니티

### language
- c 언어
- 파이썬
- 자바
- c++
- swift
- html,css,javascript + webgl

### backend
- docker

### database
- mysql

----

## 프로젝트 이력

### 유니티
<img src='./images/ZombieSurvival.png' width="150" />

- 소개:좀비를 무찌르고 끝까지 살아남는 게임
- 기말 프로젝트 발표

### 컴퓨터 그래픽스(Webgl)


#### Content
The main content for you resume will all come under the content property in the `_config.yml` file. This can be quite complex and a good understanding on [YAML](https://docs.ansible.com/ansible/latest/reference_appendices/YAMLSyntax.html) will be helpful here.

Content will contain an array of sections, there are currently 2 types of layouts for content sections, text and list.

**text** is a basic layout that contains markdown content.  
**list** is a the standard layout that is used for things like *Education* and *Experience*.

Below is a the full list of content options.
```
content:
  - title: Section Name
    layout: list (options: list, text)
    content:
      - layout: left (options: left, right, top, top-right, top-middle)(default: left)
        title: Name of item (eg. Company or Project name)
        sub_title: Sub title (eg. Qualification or Job title)(optional)
        caption: Item caption (eg. Employment or course dates)(optional)
        link: Web link (eg. https://sproogen.github.io/modern-resume-theme)(optional)
        link_text: Text for link (optional: without this link will show URL as link text)
        additional_links: (optional)
          - title: Link name
            icon: Font Awesome brand icon name (eg. fab fa-twitter) (https://fontawesome.com/icons?d=gallery&s=brands&m=free)
            url: Link url (eg. https://google.com)
        quote: >
          Short overview or quote for the item
        description: | # this will include new lines to allow paragraphs
          Main content area for the list item.
  - title: Section Name
    layout: text (options: list, text)
    content: | # this will include new lines to allow paragraphs
      This is where you can write a little more about yourself. You could title this section **Interests** and include some of your other interests.

      Or you could title it **Skills** and write a bit more about things that make you more desirable, like *leadership* or *teamwork*
```

***Note:** The description or content areas (fields starting with `| #`) use markdown, this means that you have the ability to format the section in many different ways and add things such as images, code & syntax highlighting and tables. You can find a good [Markdown cheatsheet here](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)*

#### Additional links
If you would like to add more than the predefined social links in the config file, then you can use the `additional_links` field to add as many additional links with urls and font awesome icons as you wish.

#### Dark Mode
Dark mode is configured via `_config.yml`  
```
darkmode: true (options: true, false, never)
```
When dark mode is `true` the site will show the dark theme for everyone  
When dark mode is `false` the site will not show the dark theme, but it will still respect the users device preferences  
When dark mode is `never` the site will never be shown in the dark theme

#### Heading Anchors
You can link to section titles using a Markdown anchor link, e.g.: `[About me](#about-me)`. The link after the `#` is the slug version of the title.

### `assets/main.scss`
Add any css changes or additions you want to make here after the line `@import 'modern-resume-theme';`

----

## Running locally

Before you start make sure you have *Ruby* and the gems for *Jekyll* installed locally. You can find out how to do that [here](https://jekyllrb.com/docs/installation/).

1. Clone your resume repository locally *(if you haven't already)*
2. `cd [your-repository-name]`
3. `bundle install`
4. `bundle exec jekyll serve`
5. Open your browser to `http://localhost:4000`

Any changes you make will automatically build and you will be able to see these by refreshing your browser.

*Note: You will need to re-run `bundle exec jekyll serve` to see changes made in `_config.yml`.*

----

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/sproogen/modern-resume-theme. You can view our full guide to contributing [here](https://github.com/sproogen/modern-resume-theme/blob/master/CONTRIBUTING.md)
This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

----

## Development

### Locally

Before you start make sure you have *Ruby* and the gems for *Jekyll* installed locally. You can find out how to do that [here](https://jekyllrb.com/docs/installation/).

*Note: You will need version `1.15.2` of bundler, as this is the only version that Heroku supports.*

1. Fork and or clone this repository locally
2. `cd modern-resume-theme`
3. `bundle install`
4. `bundle exec jekyll serve`
5. Open your browser to `http://localhost:4000`

Any changes you make will automatically build and you will be able to see these by refreshing your browser. To find out more about *Jekyll* take a look [here](https://jekyllrb.com/docs/usage/).

***Note:** You will need to re-run `bundle exec jekyll serve` to see changes made in `_config.yml`.*

### Docker

If you have docker installed you can simply run `docker-compose up` to launch the site in a container, it will then be hosted at `http://localhost:4000`

----

## License

The theme is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
