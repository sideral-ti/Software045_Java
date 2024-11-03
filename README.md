# Crud avanzado de la entidad Portafolio


```java
@Entity
public class Portfolio {
    @Id
    @GeneratedValue(strategy = GenerationType.IDENTITY)
    private Long id;
    private String title;
    private String description;
    private String imageUrl;
    private String category;
    private LocalDate creationDate;
    private boolean featured;
}
```

