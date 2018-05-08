AWS Credentials must be placed in a `settings.xml` file under the `./m2` directory.

https://github.com/davidmoten/aws-maven-plugin 

`/m2.settings.xml`

```
<settings>
    <servers>
        <server>
            <id>aws-lambda</id>
            <username>{ACCESS_ID}</username>
            <password>{SECRET_KEY}</password>
        </server>
    </servers>
</settings>
```