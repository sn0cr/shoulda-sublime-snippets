# Shoulda matchers snippets for Sublime text 2
______________________________

## Get started
```bash
cd /to/your/sublime/packages/dir
git clone https://github.com/sn0cr/shoulda-sublime-snippets.git
```

## Snippets

### Active Model

```ruby
itsvp: it { should validate_presence_of(:tab) }
itsvu: it { should validate_uniqueness_of(:tab) }
itsei: it { should ensure_inclusion_of(:tab).in_array(["a", "b"])}
```
### Active Record

```ruby
itsbt: it { should belong_to(:tab)}
itshm: it { should have_many(:tabs)}
```
### Active Controller

```ruby
itsrw: it {should respond_with(:tabs)}
itsrt: it { should render_template("tabs/all")}
```
